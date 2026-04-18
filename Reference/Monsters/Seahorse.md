---
type: pc
race: "Beast"
class:
 - "Seahorse"
subClass:
 - "CR 0"
cover: "Seahorse.png"
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
###### Seahorse
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Seahorse.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Beast |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 1 (1d4 - 1) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 12 | 8 | 1 | 10 | 2 |
| **Mod** | -5 | +1 | -1 | -5 | +0 | -4 |

**Speed:** 5 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** —
**Skills:** Perception +2, Stealth +5

---

### Traits

**Water Breathing.** The seahorse can breathe only underwater.


---

### Actions

**Bubble Dash.** While underwater, the seahorse moves up to its Swim Speed without provoking Opportunity Attacks.


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