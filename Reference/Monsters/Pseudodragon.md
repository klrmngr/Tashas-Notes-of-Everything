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
  - source/mm
---
###### Pseudodragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
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
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 7 (2d4 + 2) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 15 | 13 | 10 | 12 | 10 |
| **Mod** | -2 | +2 | +1 | +0 | +1 | +0 |

**Speed:** 15 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 13
**Languages:** understands Common and Draconic but can't speak
**Skills:** Perception +3, Stealth +4

---

### Traits

**Keen Senses.** The pseudodragon has advantage on Wisdom (Perception) checks that rely on sight, hearing, or smell.

**Magic Resistance.** The pseudodragon has advantage on saving throws against spells and other magical effects.

**Limited Telepathy.** The pseudodragon can magically communicate simple ideas, emotions, and images telepathically with any creature within 100 feet of it that can understand a language.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Sting.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage, and the target must succeed on a DC 11 Constitution saving throw or become poisoned for 1 hour. If the saving throw fails by 5 or more, the target falls unconscious for the same duration, or until it takes damage or another creature uses an action to shake it awake.


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