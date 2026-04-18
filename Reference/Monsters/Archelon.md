---
type: pc
race: "Beast (dinosaur)"
class:
 - "Archelon"
subClass:
 - "CR 4"
cover: "Archelon.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/4
  - source/xmm
---
###### Archelon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Archelon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Huge Beast (dinosaur) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 90 (12d12 + 12) |
> | :FasUserGroup: Race | Beast (dinosaur) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 13 | 4 | 14 | 6 |
| **Mod** | +4 | +3 | +1 | -3 | +2 | -2 |

**Speed:** 20 ft., swim 80 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** —
**Skills:** Stealth +5

---

### Traits

**Amphibious.** The archelon can breathe air and water.


---

### Actions

**Multiattack.** The archelon makes two Bite attacks.

**Bite.** m +6, reach 5 ft. *Hit:* 14 (3d6 + 4) Piercing damage.


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