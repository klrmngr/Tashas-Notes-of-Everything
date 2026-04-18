---
type: pc
race: "Dragon"
class:
 - "Faerie Dragon Adult"
subClass:
 - "CR 2"
cover: "Faerie Dragon Adult.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/tiny
  - cr/2
  - source/xmm
---
###### Faerie Dragon Adult
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Faerie Dragon Adult.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Tiny Dragon |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 35 (10d4 + 10) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 20 | 13 | 14 | 12 | 16 |
| **Mod** | -4 | +5 | +1 | +2 | +1 | +3 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Draconic, Sylvan; telepathy 60 ft. (faerie dragons only)
**Skills:** Arcana +4, Perception +3, Stealth +7

---

### Traits

**Magic Resistance.** The dragon has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Bite.** m +7, reach 5 ft. *Hit:* 7 (1d4 + 5) Piercing damage plus 3 (1d6) Psychic damage.

**Euphoria Breath (Recharge 5–6).** wis DC 13, each creature in a 15-foot Cone.  The target has the Incapacitated condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. While Incapacitated, the target uses all its movement on each of its turns to move in a random direction.


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