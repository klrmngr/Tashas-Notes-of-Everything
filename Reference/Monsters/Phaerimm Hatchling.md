---
type: pc
race: "Aberration"
class:
 - "Phaerimm Hatchling"
subClass:
 - "CR 1/4"
cover: "Phaerimm Hatchling.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/1-4
  - source/fraif
---
###### Phaerimm Hatchling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Phaerimm Hatchling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 12 | 14 | 16 | 14 |
| **Mod** | +0 | +1 | +1 | +2 | +3 | +2 |

**Speed:** 10 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 60 ft., passive Perception 15
**Languages:** telepathy 30 ft. understands Common and Deep Speech but can't speak
**Skills:** Perception +5
**Condition Immunities:** charmed

---

### Traits

**Magic Resistance.** The phaerimm has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The phaerimm makes two Stinger attacks.

**Stinger.** m +3, reach 5 ft. *Hit:* 3 (1d4 + 1) Piercing damage.


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