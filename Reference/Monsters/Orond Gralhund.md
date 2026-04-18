---
type: pc
race: "Humanoid (human)"
class:
 - "Orond Gralhund"
subClass:
 - "CR —"
cover: "Orond Gralhund.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/wdh
---
###### Orond Gralhund
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Orond Gralhund.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | — |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 9 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | -1 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** Common

---

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