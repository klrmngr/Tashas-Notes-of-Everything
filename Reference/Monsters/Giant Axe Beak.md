---
type: pc
race: "Monstrosity"
class:
 - "Giant Axe Beak"
subClass:
 - "CR 5"
cover: "Giant Axe Beak.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/5
  - source/xmm
---
###### Giant Axe Beak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Axe Beak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 84 (8d12 + 32) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 14 | 19 | 3 | 12 | 5 |
| **Mod** | +5 | +2 | +4 | -4 | +1 | -3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Skills:** Perception +4

---

### Actions

**Multiattack.** The axe beak makes one Sharpened Beak attack and one Talons attack.

**Sharpened Beak.** m +8, reach 10 ft. *Hit:* 18 (2d12 + 5) Slashing damage, and a creature within 5 feet of the target (axe beak's choice) takes 6 (1d12) Slashing damage.

**Talons.** m +8, reach 5 ft. *Hit:* 14 (2d8 + 5) Piercing damage. If the target is a Large or smaller creature, it has the Prone condition.


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