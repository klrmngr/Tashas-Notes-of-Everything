---
type: pc
race: "Humanoid (derro)"
class:
 - "Narrak"
subClass:
 - "CR 2"
cover: "Narrak.png"
campaign:
locations:
tags:
  - race/derro
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/oota
---
###### Narrak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Narrak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (derro) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 40 (9d6 + 9) |
> | :FasUserGroup: Race | Humanoid (derro) |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 13 | 14 | 5 | 16 |
| **Mod** | -1 | +2 | +1 | +2 | -3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 7
**Languages:** Dwarvish, Undercommon
**Skills:** Arcana +4, Stealth +4

---

### Traits

**Insanity.** Narrak has advantage on saving throws against being charmed or frightened.

**Magic Resistance.** Narrak has advantage on saving throws against spells and other magical effects.

**Sunlight Sensitivity.** While in sunlight, Narrak has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Armor of Shadows (Recharges after a Short or Long Rest).** Narrak casts mage armor on himself

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**One with Shadows.** While he is in a dim light or darkness, Narrak can become invisible. He remains so until he moves or takes an action or reaction.


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