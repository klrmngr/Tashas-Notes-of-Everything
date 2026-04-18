---
type: pc
race: "Humanoid (kobold)"
class:
 - "Icewind Kobold"
subClass:
 - "CR 1/8"
cover: "Icewind Kobold.png"
campaign:
locations:
tags:
  - race/kobold
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-8
  - source/idrotf
---
###### Icewind Kobold
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Icewind Kobold.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Humanoid (kobold) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 9 (2d6 + 2) |
> | :FasUserGroup: Race | Humanoid (kobold) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 15 | 12 | 8 | 8 | 8 |
| **Mod** | -2 | +2 | +1 | -1 | -1 | -1 |

**Speed:** 30 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Draconic
**Saving Throws:** Dex +4, Con +3
**Skills:** Perception +1, Stealth +4, Survival +1

---

### Traits

**Pack Tactics.** The kobold has advantage on an attack roll against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Sunlight Sensitivity.** While in sunlight, the kobold has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Javelin.** Melee or Ranged Weapon Attack: +0 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 1 (1d6 - 2) piercing damage.


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