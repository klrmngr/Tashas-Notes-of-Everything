---
type: pc
race: "Humanoid (any race)"
class:
 - "Illusionist"
subClass:
 - "CR 3"
cover: "Illusionist.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/vgm
---
###### Illusionist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Illusionist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 13 | 16 | 11 | 12 |
| **Mod** | -1 | +2 | +1 | +3 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** any four languages
**Saving Throws:** Int +5, Wis +2
**Skills:** Arcana +5, History +5

---

### Traits

**Displacement (Recharges after the Illusionist Casts an Illusion Spell of 1st Level or Higher).** As a bonus action, the illusionist projects an illusion that makes the illusionist appear to be standing in a place a few inches from its actual location, causing any creature to have disadvantage on attack rolls against the illusionist. The effect ends if the illusionist takes damage, it is incapacitated, or its speed becomes 0.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two hands.


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