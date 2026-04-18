---
type: pc
race: "Humanoid (elf)"
class:
 - "Remallia Haventree"
subClass:
 - "CR 9"
cover: "Remallia Haventree.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/wdh
---
###### Remallia Haventree
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Remallia Haventree.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 13 | 18 | 15 | 17 |
| **Mod** | +0 | +2 | +1 | +4 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Draconic, Dwarvish, Elvish, Halfling
**Saving Throws:** Int +8, Wis +6
**Skills:** Arcana +8, Deception +7, History +8, Persuasion +7

---

### Traits

**Special Equipment.** Remallia has a figurine of wondrous power (silver raven).

**Fey Ancestry.** Remallia has advantage on saving throws against being charmed, and magic can't put her to sleep.

**Arcane Ward.** Remallia has a magical ward that has 30 hit points. Whenever she takes damage, the ward takes the damage instead. If the ward is reduced to 0 hit points, Remallia takes any remaining damage. When Remallia casts an abjuration spell of 1st level or higher, the ward regains a number of hit points equal to twice the level of the spell. This applies to any of the following spells she casts: alarm, mage armor, shield, arcane lock, counterspell, dispel magic, banishment, stoneskin, globe of invulnerability and symbol.


---

### Actions

**Dagger.** Melee Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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