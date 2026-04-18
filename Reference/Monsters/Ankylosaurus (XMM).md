---
type: pc
race: "Beast (dinosaur)"
class:
 - "Ankylosaurus"
subClass:
 - "CR 3"
cover: "Ankylosaurus.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/3
  - source/xmm
---
###### Ankylosaurus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ankylosaurus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Huge Beast (dinosaur) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 68 (8d12 + 16) |
> | :FasUserGroup: Race | Beast (dinosaur) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 15 | 2 | 12 | 5 |
| **Mod** | +4 | +0 | +2 | -4 | +1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —
**Saving Throws:** Str +6

---

### Actions

**Multiattack.** The ankylosaurus makes two Tail attacks.

**Tail.** m +6, reach 10 ft. *Hit:* 9 (1d10 + 4) Bludgeoning damage. If the target is a Huge or smaller creature, it has the Prone condition.


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