---
type: pc
race: "Beast"
class:
 - "Dire Wolf"
subClass:
 - "CR 1"
cover: "Dire Wolf.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1
  - source/xmm
---
###### Dire Wolf
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Dire Wolf.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 22 (3d10 + 6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 15 | 3 | 12 | 7 |
| **Mod** | +3 | +2 | +2 | -4 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5, Stealth +4

---

### Traits

**Pack Tactics.** The wolf has Advantage on an attack roll against a creature if at least one of the wolf's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Bite.** m +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Piercing damage. If the target is a Large or smaller creature, it has the Prone condition.


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