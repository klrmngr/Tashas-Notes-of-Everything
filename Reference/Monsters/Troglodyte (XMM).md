---
type: pc
race: "Monstrosity"
class:
 - "Troglodyte"
subClass:
 - "CR 1/4"
cover: "Troglodyte.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1-4
  - source/xmm
---
###### Troglodyte
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Troglodyte.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 6 | 10 | 6 |
| **Mod** | +2 | +0 | +2 | -2 | +0 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Troglodyte
**Skills:** Stealth +4

---

### Traits

**Stench.** con DC 12, any creature (other than a troglodyte) that starts its turn in a 5-foot Emanation originating from the troglodyte.  The target has the Poisoned condition until the start of its next turn.  The target is immune to the Stench of all troglodytes for 1 hour.

**Sunlight Sensitivity.** While in sunlight, the troglodyte has Disadvantage on ability checks and attack rolls.


---

### Actions

**Rend.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Slashing damage.


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