---
type: pc
race: "Beast"
class:
 - "Hunter Shark"
subClass:
 - "CR 2"
cover: "Hunter Shark.png"
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
###### Hunter Shark
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Hunter Shark.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 1 | 10 | 4 |
| **Mod** | +4 | +2 | +2 | -5 | +0 | -3 |

**Speed:** 5 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 12
**Languages:** —
**Skills:** Perception +2

---

### Traits

**Water Breathing.** The shark can breathe only underwater.


---

### Actions

**Bite.** m +6 (with Advantage if the target doesn't have all its Hit Points), reach 5 ft. *Hit:* 14 (3d6 + 4) Piercing damage.


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