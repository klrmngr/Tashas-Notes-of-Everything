---
type: pc
race: "Monstrosity"
class:
 - "Hippogriff"
subClass:
 - "CR 1"
cover: "Hippogriff.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/1
  - source/xmm
---
###### Hippogriff
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Hippogriff.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 26 (4d10 + 4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 13 | 13 | 2 | 12 | 8 |
| **Mod** | +3 | +1 | +1 | -4 | +1 | -1 |

**Speed:** 40 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** —
**Skills:** Perception +5

---

### Traits

**Flyby.** The hippogriff doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The hippogriff makes two Rend attacks.

**Rend.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing damage.


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