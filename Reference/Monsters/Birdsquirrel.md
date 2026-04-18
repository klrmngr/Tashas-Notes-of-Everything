---
type: pc
race: "Beast"
class:
 - "Birdsquirrel"
subClass:
 - "CR 1/4"
cover: "Birdsquirrel.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/tiny
  - cr/1-4
  - source/awm
---
###### Birdsquirrel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Birdsquirrel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Beast |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 10 |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 13 | 4 | 12 | 6 |
| **Mod** | -2 | +2 | +1 | -3 | +1 | -2 |

**Speed:** 20 ft., climb 20 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Pack Tactics.** Birdsquirrel has advantage on an attack roll against a creature if at least one of the Birdsquirrel's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** Birdsquirrel makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6+2) piercing damage.

**Claws.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4+2) slashing damage.


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