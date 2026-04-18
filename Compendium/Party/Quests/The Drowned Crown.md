---
type: quest
target: groupQuest
campaign: "THE DROWNED CROWN"
locations:
 - "[[Tomb of Sand]]"
tags:
 - quest/ongoing
---
###### The Drowned Crown
<span class="sub2">:FasCircleExclamation: Quest &nbsp; | &nbsp; :FasListCheck: Ongoing</span>
___

> [!quote|no-t]
> ![[quest.png|right wm-sm]]A crown of dark power lies sealed in an ancient burial chamber beneath the desert — guarded by [[The Drowned Eternal]], a Sea Lich mid-ritual. The party must navigate the [[Elven Harbour]], survive a Drow intercept at sea, and descend through the [[Ancient Stepwell]] into the [[Tomb of Sand]] to claim or destroy the crown before the lich's ceremony is complete.

> [!column|flex 3]
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```
