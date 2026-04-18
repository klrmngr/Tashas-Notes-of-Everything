---
type: pc
race: "Beast"
class:
 - "Giant Bat"
subClass:
 - "CR 1/4"
cover: "Giant Bat.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1-4
  - source/mm
---
###### Giant Bat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Giant Bat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (4d10) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 11 | 2 | 12 | 6 |
| **Mod** | +2 | +3 | +0 | -4 | +1 | -2 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 11
**Languages:** —

---

### Traits

**Echolocation.** The bat can't use its blindsight while deafened.

**Keen Hearing.** The bat has advantage on Wisdom (Perception) checks that rely on hearing.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 5 (1d6 + 2) piercing damage.


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