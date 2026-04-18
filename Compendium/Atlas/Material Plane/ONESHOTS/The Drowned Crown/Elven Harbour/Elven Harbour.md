---
type: locale
campaign: "THE DROWNED CROWN"
locations:
 - ""
tags:
 - location/harbour
---
![[banner.jpg|banner]]
###### Elven Harbour
<span class="sub2">:FasAnchor: Harbour</span>
___

> [!quote|no-t] SUMMARY
> A bustling elven port town serving as the departure point for the party's voyage. The [[Dockmaster]] here has been tracking Drow fleet movements and can point the party toward the fleet's heading. Vessels can be hired or stolen from the docks.

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
