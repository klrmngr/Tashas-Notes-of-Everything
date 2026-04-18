---
type: npc
campaign: "THE DROWNED CROWN"
locations:
  - "[[Elven Harbour]]"
tags:
  - affinity/friendly
  - job/dockmaster
  - campaign/theDrownedCrown
---
###### Dockmaster
<span class="sub2">:FasMapLocationDot: [[Elven Harbour]] &nbsp; | &nbsp; :FasHeartPulse: Friendly</span>
___

> [!infobox|no-t right]
> ![[Dockmaster.webp]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasBriefcase: Job | Dockmaster |
> | :FasVenusMars: Gender | — |
> | :FasUser: Race | — |

> [!quote|no-t]
> The dockmaster of the Elven Harbour. Has been tracking Drow fleet movements and holds intel on their heading — a critical contact for the party at the start of the one-shot.

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
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
