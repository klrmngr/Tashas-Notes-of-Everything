---
type: pc
race: "Beast"
class:
 - "Giant Crocodile"
subClass:
 - "CR 5"
cover: "Giant Crocodile.png"
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
###### Giant Crocodile
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Crocodile.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 85 (9d12 + 27) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 9 | 17 | 2 | 10 | 7 |
| **Mod** | +5 | -1 | +3 | -4 | +0 | -2 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Skills:** Stealth +5

---

### Traits

**Hold Breath.** The crocodile can hold its breath for 1 hour.


---

### Actions

**Multiattack.** The crocodile makes one Bite attack and one Tail attack.

**Bite.** m +8, reach 5 ft. *Hit:* 21 (3d10 + 5) Piercing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 15). While Grappled, the target has the Restrained condition and can't be targeted by the crocodile's Tail.

**Tail.** m +8, reach 10 ft. *Hit:* 18 (3d8 + 5) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.


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