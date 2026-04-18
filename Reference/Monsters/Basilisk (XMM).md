---
type: pc
race: "Monstrosity"
class:
 - "Basilisk"
subClass:
 - "CR 3"
cover: "Basilisk.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/xmm
---
###### Basilisk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Basilisk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 8 | 15 | 2 | 8 | 7 |
| **Mod** | +3 | -1 | +2 | -4 | -1 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 9
**Languages:** —

---

### Actions

**Bite.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Piercing damage plus 7 (2d6) Poison damage.


---

### Bonus Actions

**Petrifying Gaze (Recharge 4–6).** con DC 12, each creature in a 30-foot Cone. If the basilisk sees its reflection within the Cone, the basilisk must make this save. 1 The target has the Restrained condition and repeats the save at the end of its next turn if it is still Restrained, ending the effect on itself on a success. 2 The target has the Petrified condition instead of the Restrained condition.


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