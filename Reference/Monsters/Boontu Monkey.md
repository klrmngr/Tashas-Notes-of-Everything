---
type: pc
race: "Beast"
class:
 - "Boontu Monkey"
subClass:
 - "CR 0"
cover: "Boontu Monkey.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/0
  - source/awm
---
###### Boontu Monkey
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Boontu Monkey.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Beast |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 3 |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 11 | 5 | 12 | 6 |
| **Mod** | -1 | +2 | +0 | -3 | +1 | -2 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Pack Tactics.** The Boontu monkey has advantage on an attack roll against a creature if at least one of the boontu monkey's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Bite.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 1 (1d4 - 1) piercing damage.


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