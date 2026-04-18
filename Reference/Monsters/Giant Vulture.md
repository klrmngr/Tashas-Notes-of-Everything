---
type: pc
race: "Beast"
class:
 - "Giant Vulture"
subClass:
 - "CR 1"
cover: "Giant Vulture.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1
  - source/mm
---
###### Giant Vulture
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Giant Vulture.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 22 (3d10 + 6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 15 | 6 | 12 | 7 |
| **Mod** | +2 | +0 | +2 | -2 | +1 | -2 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** understands Common but can't speak
**Skills:** Perception +3

---

### Traits

**Keen Sight and Smell.** The vulture has advantage on Wisdom (Perception) checks that rely on sight or smell.

**Pack Tactics.** The vulture has advantage on an attack roll against a creature if at least one of the vulture's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The vulture makes two attacks: one with its beak and one with its talons.

**Beak.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) piercing damage.

**Talons.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage.


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