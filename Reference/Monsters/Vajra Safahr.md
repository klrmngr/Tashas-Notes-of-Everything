---
type: pc
race: "Humanoid (human)"
class:
 - "Vajra Safahr"
subClass:
 - "CR 13"
cover: "Vajra Safahr.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/13
  - source/wdh
---
###### Vajra Safahr
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Vajra Safahr.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 14; 17 with mage armor |
> | :FasHeart: HP | 126 (23d8 + 23) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 20 | 11 | 16 |
| **Mod** | +0 | +2 | +1 | +5 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Dwarvish, Elvish, Giant, Halfling, Undercommon
**Saving Throws:** Str +2, Dex +4, Con +3, Int +12, Wis +7, Cha +5
**Skills:** Arcana +10, History +10

---

### Traits

**Special Equipment.** Vajra wields the Blackstaff, accounted for in her statistics. Roll 2d10 to determine how many charges the staff has remaining.

**Magic Resistance.** Vajra has advantage on saving throws against spells and other magical effects.

**Staff Spells.** While holding the Blackstaff, Vajra can use an action to expend 1 or more of its charges to cast one of the following spells from it, using her spell save DC and spell attack bonus: cone of cold (5 charges), fireball (5th-level version, 5 charges), globe of invulnerability (6 charges), hold monster (5 charges), levitate (2 charges), lightning bolt (5th-level version, 5 charges), magic missile (1 charge), ray of enfeeblement (1 charge), or wall of force (5 charges).


---

### Actions

**Blackstaff.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning, magic damage, or 6 (1d8 + 2) bludgeoning, magic damage when used with two hands. Vajra can expend 1 of the staff's charges to deal an extra 3 (1d6) force damage on a hit.


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