---
type: pc
race: "Beast"
class:
 - "Owl"
subClass:
 - "CR 0"
cover: "Owl.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/tiny
  - cr/0
  - source/mm
---
###### Owl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Owl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Beast |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 1 (1d4 - 1) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 13 | 8 | 2 | 12 | 7 |
| **Mod** | -4 | +1 | -1 | -4 | +1 | -2 |

**Speed:** 5 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +3

---

### Traits

**Flyby.** The owl doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Keen Hearing and Sight.** The owl has advantage on Wisdom (Perception) checks that rely on hearing or sight.


---

### Actions

**Talons.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 1 slashing damage.


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