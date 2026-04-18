---
type: pc
race: "Humanoid (kobold)"
class:
 - "Winged Kobold"
subClass:
 - "CR 1/4"
cover: "Winged Kobold.png"
campaign:
locations:
tags:
  - race/kobold
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/mm
---
###### Winged Kobold
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Winged Kobold.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (kobold) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 7 (3d6 - 3) |
> | :FasUserGroup: Race | Humanoid (kobold) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 16 | 9 | 8 | 7 | 8 |
| **Mod** | -2 | +3 | -1 | -1 | -2 | -1 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** Common, Draconic

---

### Traits

**Sunlight Sensitivity.** While in sunlight, the kobold has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Pack Tactics.** The kobold has advantage on an attack roll against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Dropped Rock.** Ranged Weapon Attack: +5 to hit, one target directly below the kobold. *Hit:* 6 (1d6 + 3) bludgeoning damage.


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