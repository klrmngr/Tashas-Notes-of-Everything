---
type: pc
race: "Creature"
class:
 - "Jelayne"
subClass:
 - "CR —"
cover: "Jelayne.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/medium
  - cr/—
  - source/oow
---
###### Jelayne
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: OoW
___

> [!infobox|no-t right]
> ![[Jelayne.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Creature |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | — |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | OoW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 14 | 10 | 14 |
| **Mod** | +0 | +0 | +0 | +2 | +0 | +2 |

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