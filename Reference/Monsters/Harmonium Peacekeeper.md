---
type: pc
race: "Humanoid"
class:
 - "Harmonium Peacekeeper"
subClass:
 - "CR 3"
cover: "Harmonium Peacekeeper.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/mpp
---
###### Harmonium Peacekeeper
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Harmonium Peacekeeper.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 14 | 12 | 14 | 11 |
| **Mod** | +3 | +0 | +2 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus one more language
**Skills:** Perception +4

---

### Traits

**Pack Tactics.** The peacekeeper has advantage on an attack roll against a creature if at least one of the peacekeeper's allies is within 5 feet of the creature and the ally doesn't have the incapacitated condition.


---

### Actions

**Electrified Mancatcher.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage plus 4 (1d8) lightning damage. If the target is a Large or smaller creature, it has the grappled condition (escape DC 13). Until the grappled condition ends, the target has the restrained condition and can't teleport, the peacekeeper can't make Electrified Mancatcher attacks, and the target takes 8 (1d10 + 3) lightning damage at the start of each of its turns.


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