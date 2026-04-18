---
type: pc
race: "Giant"
class:
 - "Cyclops"
subClass:
 - "CR 6"
cover: "Cyclops.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/6
  - source/mm
---
###### Cyclops
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Cyclops.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 11 | 20 | 8 | 6 | 10 |
| **Mod** | +6 | +0 | +5 | -1 | -2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 8
**Languages:** Giant

---

### Traits

**Poor Depth Perception.** The cyclops has disadvantage on any attack roll against a target more than 30 feet away.


---

### Actions

**Multiattack.** The cyclops makes two greatclub attacks.

**Greatclub.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +9 to hit, range 30/120 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage.


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