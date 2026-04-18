<%*
const { toCamelCase, moveAndOpenFile } = tp.user.utils;

// Get next session number within a specific folder
function nextNumber(folder) {
    const sessionRegex = new RegExp(`^${folder}/Session (\\d+)\\.md$`);
    const max = app.vault.getMarkdownFiles()
        .reduce((maxNum, file) => Math.max(maxNum, parseInt((file.path.match(sessionRegex) || [])[1] || 0)), 0) + 1;
    return max < 10 ? '0' + max : max.toString();
}

// Open modal form for session note creation
const result = await MF.openForm('NOTE');

// Cancel if form was closed without submission
if (result.status !== 'ok') {
    new Notice().noticeEl.innerHTML = `<span style="color: red; font-weight: bold;">Cancelled:</span><br>Session note has not been added`;
    return;
}

// Declare & normalize variables
const date = result.Date.value;
const title = result.Title.value;
const location = result.Location.value ? result.Location.value.map(value => `- "[[${value}]]"`).join("\n") : '';
const banner = result.Banner.value || "session.jpg";
const type = result.Type.value || "Campaign";
const campaign = result.Campaign.value || "Unknown";
const tags = result.Tags.value
    ? result.Tags.value.map(value => value.startsWith('#') ? `- ${value.slice(1)}` : `- ${toCamelCase(value)}`).join("\n")
    : '';

// Determine folder based on type
const folder = type === "One Shot"
    ? `Session Notes/One Shots/${campaign}`
    : `Session Notes/Campaigns/${campaign}`;

const number = nextNumber(folder);
const name = `Session ${number}`;
const notePath = `${folder}/${name}`;

// Move & open note in new tab
await moveAndOpenFile(tp, name, notePath);

// Apply icon to note
const iconize = app.plugins.plugins["obsidian-icon-folder"];
const icon = "LiNoteBookPen";
iconize.addFolderIcon(`${notePath}.md`, icon);
iconize.api.util.dom.createIconNode(iconize, `${notePath}.md`, icon);

// Show success notification
new Notice().noticeEl.innerHTML = `<span style="color: green; font-weight: bold;">Finished!</span><br>New note <span style="text-decoration: underline;">${name}</span> added`;
_%>

---
type: notes
campaign: "<% campaign %>"
locations:
<% location ? location : ' - '%>
tags:
<% tags ? tags : ' - '%>
date: "<% date %>"
---
![[<% banner %>|banner]]
###### <% title %>
<span class="sub2">:FasSun: DAY 00&nbsp; | &nbsp; :FasTags: `VIEW[{tags}][text]`</span>
___

> [!quote|no-t] SUMMARY
>Recap of the session's events here.

#### marker
> [!column|flex 3]
>> [!info|felx] NPC'S:
>> - [[Character]] (status)
>
>> [!example|flex] LOCATIONS:
>> - [[Locations]] (status)
>
>> [!important|flex] QUESTS:
>> - [[Quests]] (status)
