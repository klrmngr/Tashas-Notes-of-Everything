---
type: pc
race: "Humanoid (derro)"
class:
 - "Derro"
subClass:
 - "CR 1/4"
cover: "Derro.png"
campaign:
locations:
tags:
  - race/derro
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/oota
---
###### Derro
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Derro.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (derro) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Humanoid (derro) |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 12 | 11 | 5 | 9 |
| **Mod** | -1 | +2 | +1 | +0 | -3 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 7
**Languages:** Dwarvish, Undercommon
**Skills:** Stealth +4

---

### Traits

**Insanity.** The derro has advantage on saving throws against being charmed or frightened.

**Magic Resistance.** The derro has advantage on saving throws against spells and other magical effects.

**Sunlight Sensitivity.** While in sunlight, the derro has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Hooked Shortspear.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 1 (1d4 - 1) piercing damage. If the target is a creature, the derro can choose to deal no damage and try to trip the target instead, in which case the target must succeed on a DC 9 Strength saving throw or fall prone.

**Light Repeating Crossbow.** Ranged Weapon Attack: +4 to hit, range 40/160 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


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