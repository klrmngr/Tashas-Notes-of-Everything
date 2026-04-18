---
type: pc
race: "Beast"
class:
 - "Cave Bear"
subClass:
 - "CR 2"
cover: "Cave Bear.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/2
  - source/mm
---
###### Cave Bear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Cave Bear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 42 (5d10 + 15) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 16 | 2 | 13 | 7 |
| **Mod** | +5 | +0 | +3 | -4 | +1 | -2 |

**Speed:** 40 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Traits

**Keen Smell.** The bear has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** The bear makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage.


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