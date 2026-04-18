---
type: pc
race: "Beast"
class:
 - "Giant Boar"
subClass:
 - "CR 2"
cover: "Giant Boar.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/2
  - source/xmm
---
###### Giant Boar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Boar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 42 (5d10 + 15) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 16 | 2 | 7 | 5 |
| **Mod** | +3 | +0 | +3 | -4 | -2 | -3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 8
**Languages:** —
**Saving Throws:** Str +5

---

### Traits

**Bloodied Fury.** The boar has Advantage on melee attack rolls while it is Bloodied.


---

### Actions

**Gore.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Piercing damage. If the target is a Large or smaller creature and the boar moved 20+ feet straight toward it immediately before the hit, the target takes an extra 7 (2d6) Piercing damage and has the Prone condition.


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