---
type: pc
race: "Beast"
class:
 - "Frog"
subClass:
 - "CR 0"
cover: "Frog.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/tiny
  - cr/0
  - source/xmm
---
###### Frog
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Frog.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Beast |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 1 (1d4 - 1) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 13 | 8 | 1 | 8 | 3 |
| **Mod** | -5 | +1 | -1 | -5 | -1 | -4 |

**Speed:** 20 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 30 ft., passive Perception 11
**Languages:** —
**Skills:** Perception +1, Stealth +3

---

### Traits

**Amphibious.** The frog can breathe air and water.

**Standing Leap.** The frog's Long Jump is up to 10 feet and its High Jump is up to 5 feet with or without a running start.


---

### Actions

**Bite.** m +3, reach 5 ft. *Hit:* 1 Piercing damage.


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