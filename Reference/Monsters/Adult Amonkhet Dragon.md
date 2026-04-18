---
type: pc
race: "Creature"
class:
 - "Adult Amonkhet Dragon"
subClass:
 - "CR —"
cover: "Adult Amonkhet Dragon.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/medium
  - cr/—
  - source/psa
---
###### Adult Amonkhet Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSA
___

> [!infobox|no-t right]
> ![[Adult Amonkhet Dragon.png]]
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
> | :FasBook: Source | PSA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 8 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | -1 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

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