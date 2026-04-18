---
type: locale
campaign: "THE DROWNED CROWN"
locations:
 - ""
tags:
 - location/ship
---
![[banner.jpg|banner]]
###### Drow Warship
<span class="sub2">:FasShip: Ship</span>
___

> [!quote|no-t] SUMMARY
> A Drow patrol vessel that intercepts the party mid-voyage. Use the **night variant** map. The ship is crewed by Drow sailors under a [[Drow Lieutenant]], with a [[Drow Navigator]] who holds the location of the crown. A [[Chain Devil]] is bound belowdecks as a guardian.

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
