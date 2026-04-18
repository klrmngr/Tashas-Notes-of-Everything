---
type: pc
race: "Monstrosity"
class:
 - "Death Dog"
subClass:
 - "CR 1"
cover: "Death Dog.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/xmm
---
###### Death Dog
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Death Dog.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 14 | 3 | 13 | 6 |
| **Mod** | +2 | +2 | +2 | -4 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5, Stealth +4
**Condition Immunities:** blinded; charmed; deafened; frightened; stunned; unconscious

---

### Actions

**Multiattack.** The death dog makes two Bite attacks.

**Bite.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Piercing damage. If the target is a creature, it is subjected to the following effect. con DC 12. 1 The target has the Poisoned condition. While Poisoned, the target's Hit Point maximum doesn't return to normal when finishing a Long Rest, and it repeats the save every 24 hours that elapse, ending the effect on itself on a success. Subsequent Failures: The Poisoned target's Hit Point maximum decreases by 5 (1d10).


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