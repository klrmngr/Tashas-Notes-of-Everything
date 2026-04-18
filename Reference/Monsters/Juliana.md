---
type: pc
race: "Creature"
class:
 - "Juliana"
subClass:
 - "CR —"
cover: "Juliana.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/medium
  - cr/—
  - source/qftis
---
###### Juliana
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Juliana.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Creature |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +0 | +0 |

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