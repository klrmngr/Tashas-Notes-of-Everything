---
type: pc
race: "Beast"
class:
 - "Giant Shark"
subClass:
 - "CR 5"
cover: "Giant Shark.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/5
  - source/xmm
---
###### Giant Shark
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Shark.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 92 (8d12 + 40) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 11 | 21 | 1 | 10 | 5 |
| **Mod** | +6 | +0 | +5 | -5 | +0 | -3 |

**Speed:** 5 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Traits

**Water Breathing.** The shark can breathe only underwater.


---

### Actions

**Multiattack.** The shark makes two Bite attacks.

**Bite.** m +9 (with Advantage if the target doesn't have all its Hit Points), reach 5 ft. *Hit:* 22 (3d10 + 6) Piercing damage.


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