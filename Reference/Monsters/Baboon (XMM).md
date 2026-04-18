---
type: pc
race: "Beast"
class:
 - "Baboon"
subClass:
 - "CR 0"
cover: "Baboon.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/0
  - source/xmm
---
###### Baboon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Baboon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 3 (1d6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 11 | 4 | 12 | 6 |
| **Mod** | -1 | +2 | +0 | -3 | +1 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —

---

### Traits

**Pack Tactics.** The baboon has Advantage on an attack roll against a creature if at least one of the baboon's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Bite.** m +1, reach 5 ft. *Hit:* 1 (1d4 - 1) Piercing damage.


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