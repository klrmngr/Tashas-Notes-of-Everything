---
type: pc
race: "Monstrosity"
class:
 - "Primeval Owlbear"
subClass:
 - "CR 7"
cover: "Primeval Owlbear.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/7
  - source/xmm
---
###### Primeval Owlbear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Primeval Owlbear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 126 (12d12 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 14 | 19 | 8 | 15 | 7 |
| **Mod** | +6 | +2 | +4 | -1 | +2 | -2 |

**Speed:** 40 ft., climb 40 ft., fly 5 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 18
**Languages:** —
**Saving Throws:** Con +7, Wis +5
**Skills:** Perception +8

---

### Traits

**Magic Resistance.** The owlbear has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The owlbear makes two Ravage attacks.

**Ravage.** m +9, reach 5 ft. *Hit:* 15 (2d8 + 6) Slashing damage. If the target is a Huge or smaller creature and the owlbear moved 20+ feet straight toward it immediately before the hit, the target takes an extra 9 (2d8) Slashing damage and has the Prone condition.

**Screech (Recharge 5–6).** con DC 15, each creature in a 30-foot Emanation originating from the owlbear.  27 (6d8) Thunder damage, and the target has the Incapacitated condition until the end of its next turn.  Half damage only.


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