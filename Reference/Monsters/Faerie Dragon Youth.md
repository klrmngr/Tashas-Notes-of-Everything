---
type: pc
race: "Dragon"
class:
 - "Faerie Dragon Youth"
subClass:
 - "CR 1"
cover: "Faerie Dragon Youth.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/tiny
  - cr/1
  - source/xmm
---
###### Faerie Dragon Youth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Faerie Dragon Youth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Dragon |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 21 (6d4 + 6) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 16 | 12 | 12 | 12 | 14 |
| **Mod** | -4 | +3 | +1 | +1 | +1 | +2 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Draconic, Sylvan; telepathy 60 ft. (faerie dragons only)
**Skills:** Arcana +3, Perception +3, Stealth +5

---

### Traits

**Magic Resistance.** The dragon has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Bite.** m +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Piercing damage plus 2 (1d4) Psychic damage.

**Euphoria Breath (Recharge 5–6).** wis DC 12, each creature in a 15-foot Cone.  The target has the Incapacitated condition until the end of its next turn and uses all its movement on its turn to move in a random direction.


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