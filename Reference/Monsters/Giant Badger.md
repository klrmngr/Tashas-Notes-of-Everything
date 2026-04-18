---
type: pc
race: "Beast"
class:
 - "Giant Badger"
subClass:
 - "CR 1/4"
cover: "Giant Badger.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1-4
  - source/mm
---
###### Giant Badger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Giant Badger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Beast |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 10 | 15 | 2 | 12 | 5 |
| **Mod** | +1 | +0 | +2 | -4 | +1 | -3 |

**Speed:** 30 ft., burrow 10 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 11
**Languages:** —

---

### Traits

**Keen Smell.** The badger has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** The badger makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage.

**Claws.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 6 (2d4 + 1) slashing damage.


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