---
type: pc
race: "Beast"
class:
 - "Giant Constrictor Snake"
subClass:
 - "CR 2"
cover: "Giant Constrictor Snake.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/2
  - source/xmm
---
###### Giant Constrictor Snake
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Constrictor Snake.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 60 (8d12 + 8) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 12 | 1 | 10 | 3 |
| **Mod** | +4 | +2 | +1 | -5 | +0 | -4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., passive Perception 12
**Languages:** —
**Skills:** Perception +2

---

### Actions

**Multiattack.** The snake makes one Bite attack and uses Constrict.

**Bite.** m +6, reach 10 ft. *Hit:* 11 (2d6 + 4) Piercing damage.

**Constrict.** str DC 14, one Large or smaller creature the snake can see within 10 feet.  13 (2d8 + 4) Bludgeoning damage, and the target has the Grappled condition (escape DC 14).


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