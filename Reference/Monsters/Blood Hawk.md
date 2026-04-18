---
type: pc
race: "Beast"
class:
 - "Blood Hawk"
subClass:
 - "CR 1/8"
cover: "Blood Hawk.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/1-8
  - source/mm
---
###### Blood Hawk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Blood Hawk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 10 | 3 | 14 | 5 |
| **Mod** | -2 | +2 | +0 | -4 | +2 | -3 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Skills:** Perception +4

---

### Traits

**Keen Sight.** The hawk has advantage on Wisdom (Perception) checks that rely on sight.

**Pack Tactics.** The hawk has advantage on an attack roll against a creature if at least one of the hawk's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Beak.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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