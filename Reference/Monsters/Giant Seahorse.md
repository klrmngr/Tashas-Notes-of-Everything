---
type: pc
race: "Beast"
class:
 - "Giant Seahorse"
subClass:
 - "CR 1/2"
cover: "Giant Seahorse.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1-2
  - source/xmm
---
###### Giant Seahorse
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Seahorse.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 16 (3d10) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 11 | 2 | 12 | 5 |
| **Mod** | +2 | +1 | +0 | -4 | +1 | -3 |

**Speed:** 5 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —

---

### Traits

**Water Breathing.** The seahorse can breathe only underwater.


---

### Actions

**Ram.** m +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Bludgeoning damage, or 11 (2d8 + 2) Bludgeoning damage if the seahorse moved 20+ feet straight toward the target immediately before the hit.


---

### Bonus Actions

**Bubble Dash.** While underwater, the seahorse moves up to half its Swim Speed without provoking Opportunity Attacks.


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