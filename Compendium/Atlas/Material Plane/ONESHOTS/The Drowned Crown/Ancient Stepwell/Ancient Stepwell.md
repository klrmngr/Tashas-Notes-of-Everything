---
type: locale
campaign: "THE DROWNED CROWN"
locations:
 - "[[Tomb of Sand]]"
tags:
 - location/dungeon
---
![[banner.jpg|banner]]
###### Ancient Stepwell
<span class="sub2">:FasWater: Dungeon</span>
___

> [!quote|no-t] SUMMARY
> The flooded entrance to the desert ruin complex surrounding the [[Tomb of Sand]]. Lower levels are submerged, riddled with traps, and home to territorial creatures. Harpies nest on the upper tiers; a Water Weird lurks in the flooded passages below.

> [!column|flex 3]
>> [!hint]- NPC's
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: This Location Only
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/NPC's")
>>         - locations.contains(this.file)
>> ```
>
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
