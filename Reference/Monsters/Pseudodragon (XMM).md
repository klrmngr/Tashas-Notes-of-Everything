---
type: pc
race: "Dragon"
class:
 - "Pseudodragon"
subClass:
 - "CR 1/4"
cover: "Pseudodragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/tiny
  - cr/1-4
  - source/xmm
---
###### Pseudodragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Pseudodragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Dragon |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 10 (3d4 + 3) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 15 | 13 | 10 | 12 | 10 |
| **Mod** | -2 | +2 | +1 | +0 | +1 | +0 |

**Speed:** 15 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., Darkvision 60 ft., passive Perception 15
**Languages:** understands Common and Draconic but can't speak
**Skills:** Perception +5, Stealth +4

---

### Traits

**Magic Resistance.** The pseudodragon has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The pseudodragon makes two Bite attacks.

**Bite.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Piercing damage.

**Sting.** con DC 12, one creature the pseudodragon can see within 5 feet.  5 (2d4) Poison damage, and the target has the Poisoned condition for 1 hour. While Poisoned, the target also has the Unconscious condition, which ends early if the target takes damage or a creature within 5 feet of it takes an action to wake it.


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