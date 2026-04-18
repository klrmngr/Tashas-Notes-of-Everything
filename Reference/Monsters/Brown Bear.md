---
type: pc
race: "Beast"
class:
 - "Brown Bear"
subClass:
 - "CR 1"
cover: "Brown Bear.png"
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
###### Brown Bear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Brown Bear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 34 (4d10 + 12) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 16 | 2 | 13 | 7 |
| **Mod** | +4 | +0 | +3 | -4 | +1 | -2 |

**Speed:** 40 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Traits

**Keen Smell.** The bear has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** The bear makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.


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