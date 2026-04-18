---
type: pc
race: "Humanoid (derro)"
class:
 - "Derro Savant"
subClass:
 - "CR 3"
cover: "Derro Savant.png"
campaign:
locations:
tags:
  - race/derro
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/mtf
---
###### Derro Savant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Derro Savant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid (derro) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 36 (8d6 + 8) |
> | :FasUserGroup: Race | Humanoid (derro) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 12 | 11 | 5 | 14 |
| **Mod** | -1 | +2 | +1 | +0 | -3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 7
**Languages:** Dwarvish, Undercommon
**Skills:** Stealth +4

---

### Traits

**Magic Resistance.** The derro savant has advantage on saving throws against spells and other magical effects.

**Sunlight Sensitivity.** While in sunlight, the derro savant has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) bludgeoning damage.


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