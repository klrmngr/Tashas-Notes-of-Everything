---
type: pc
race: "Beast (dinosaur)"
class:
 - "Triceratops"
subClass:
 - "CR 5"
cover: "Triceratops.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/5
  - source/xmm
---
###### Triceratops
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Triceratops.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Beast (dinosaur) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 114 (12d12 + 36) |
> | :FasUserGroup: Race | Beast (dinosaur) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 9 | 17 | 2 | 11 | 5 |
| **Mod** | +6 | -1 | +3 | -4 | +0 | -3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —

---

### Actions

**Multiattack.** The triceratops makes two Gore attacks.

**Gore.** m +9, reach 5 ft. *Hit:* 19 (2d12 + 6) Piercing damage. If the target is Huge or smaller and the triceratops moved 20+ feet straight toward it immediately before the hit, the target takes an extra 9 (2d8) Piercing damage and has the Prone condition.


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