---
type: pc
race: "Humanoid (kobold)"
class:
 - "Yusdrayl"
subClass:
 - "CR 1"
cover: "Yusdrayl.png"
campaign:
locations:
tags:
  - race/kobold
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/tftyp
---
###### Yusdrayl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Yusdrayl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid (kobold) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 16 (3d6 + 6) |
> | :FasUserGroup: Race | Humanoid (kobold) |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 15 | 14 | 10 | 10 | 16 |
| **Mod** | -1 | +2 | +2 | +0 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic
**Skills:** Arcana +2, Insight +2, Stealth +4

---

### Traits

**Sunlight Sensitivity.** While in sunlight, Yusdrayl has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Pack Tactics.** Yusdrayl has advantage on an attack roll against a creature if at least one of her allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Dagger.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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