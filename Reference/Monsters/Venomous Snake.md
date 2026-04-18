---
type: pc
race: "Beast"
class:
 - "Venomous Snake"
subClass:
 - "CR 1/8"
cover: "Venomous Snake.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/tiny
  - cr/1-8
  - source/xmm
---
###### Venomous Snake
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Venomous Snake.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Beast |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 5 (2d4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 15 | 11 | 1 | 10 | 3 |
| **Mod** | -4 | +2 | +0 | -5 | +0 | -4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., passive Perception 10
**Languages:** —

---

### Actions

**Bite.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Piercing damage plus 3 (1d6) Poison damage.


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