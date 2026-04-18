---
type: pc
race: "Beast (dinosaur)"
class:
 - "Tyrannosaurus Rex"
subClass:
 - "CR 8"
cover: "Tyrannosaurus Rex.png"
campaign:
locations:
tags:
  - race/dinosaur
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/8
  - source/xmm
---
###### Tyrannosaurus Rex
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Tyrannosaurus Rex.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Beast (dinosaur) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 136 (13d12 + 52) |
> | :FasUserGroup: Race | Beast (dinosaur) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 19 | 2 | 12 | 9 |
| **Mod** | +7 | +0 | +4 | -4 | +1 | -1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Saving Throws:** Str +10, Wis +4
**Skills:** Perception +4

---

### Actions

**Multiattack.** The tyrannosaurus makes one Bite attack and one Tail attack.

**Bite.** m +10, reach 10 ft. *Hit:* 33 (4d12 + 7) Piercing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 17). While Grappled, the target has the Restrained condition and can't be targeted by the tyrannosaurus's Tail.

**Tail.** m +10, reach 15 ft. *Hit:* 25 (4d8 + 7) Bludgeoning damage. If the target is a Huge or smaller creature, it has the Prone condition.


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