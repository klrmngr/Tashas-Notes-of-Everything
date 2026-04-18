---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow Inquisitor"
subClass:
 - "CR 14"
cover: "Drow Inquisitor.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/14
  - source/mtf
---
###### Drow Inquisitor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Drow Inquisitor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 14 | 16 | 21 | 20 |
| **Mod** | +0 | +2 | +2 | +3 | +5 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 20
**Languages:** Elvish, Undercommon
**Saving Throws:** Con +7, Wis +10, Cha +10
**Skills:** Insight +10, Perception +10, Religion +8, Stealth +7
**Condition Immunities:** frightened

---

### Traits

**Discern Lie.** The drow knows when she hears a creature speak a lie in a language she knows.

**Fey Ancestry.** The drow has advantage on saving throws against being charmed, and magic can't put the drow to sleep.

**Magic Resistance.** The drow has advantage on saving throws against spells and other magical effects.

**Sunlight Sensitivity.** While in sunlight, the drow has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The drow makes three death lance attacks.

**Death Lance.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage plus 18 (4d8) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage it takes. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.


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