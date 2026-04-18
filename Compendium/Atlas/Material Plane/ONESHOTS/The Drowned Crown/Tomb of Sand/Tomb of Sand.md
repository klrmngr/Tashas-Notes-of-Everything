---
type: locale
campaign: "THE DROWNED CROWN"
locations:
 - ""
tags:
 - location/tomb
---
![[banner.jpg|banner]]
###### Tomb of Sand
<span class="sub2">:FasSkull: Tomb</span>
___

> [!quote|no-t] SUMMARY
> A partially submerged desert ruin complex. The exterior connects through the [[Ancient Stepwell]] entrance above. The interior burial chamber holds the crown — and [[The Drowned Eternal]], a Sea Lich still mid-ritual in the central pool.

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
>> [!example]- LOCATIONS
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Landmarks
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Atlas")
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
