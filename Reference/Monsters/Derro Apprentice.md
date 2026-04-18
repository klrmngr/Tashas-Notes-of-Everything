---
type: pc
race: "Aberration"
class:
 - "Derro Apprentice"
subClass:
 - "CR 1"
cover: "Derro Apprentice.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/1
  - source/qftis
---
###### Derro Apprentice
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Derro Apprentice.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 22 (5d6 + 5) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 12 | 11 | 5 | 12 |
| **Mod** | -1 | +2 | +1 | +0 | -3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 7
**Languages:** Dwarvish, Undercommon
**Skills:** Stealth +4

---

### Traits

**Magic Resistance.** The derro has advantage on saving throws against spells and other magical effects.

**Sunlight Sensitivity.** While in sunlight, the derro has disadvantage on attack rolls.


---

### Actions

**Chaos Blast.** Melee or Ranged Spell Attack: +3 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 10 (3d6) damage. Roll a d4 to determine the damage type: 1, acid; 2, cold; 3, fire; 4, lightning.

**Force Burst (Recharge 4–6).** Raw arcane magic bursts out from the derro. Each creature within 10 feet of it must make a DC 11 Strength saving throw. On a failed save, the creature takes 7 (2d6) force damage and has the prone condition. On a successful save, the creature takes half as much damage only.


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