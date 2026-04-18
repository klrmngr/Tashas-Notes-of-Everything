---
type: pc
race: "Monstrosity"
class:
 - "Cockatrice"
subClass:
 - "CR 1/2"
cover: "Cockatrice.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/1-2
  - source/xmm
---
###### Cockatrice
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Cockatrice.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 22 (5d6 + 5) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 12 | 12 | 2 | 13 | 5 |
| **Mod** | -2 | +1 | +1 | -4 | +1 | -3 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** —
**Condition Immunities:** petrified

---

### Actions

**Petrifying Bite.** m +3, reach 5 ft. *Hit:* 3 (1d4 + 1) Piercing damage. If the target is a creature, it is subjected to the following effect. con DC 11. 1 The target has the Restrained condition. The target repeats the save at the end of its next turn if it is still Restrained, ending the effect on itself on a success. 2 The target has the Petrified condition, instead of the Restrained condition, for 24 hours.


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