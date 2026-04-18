---
type: pc
race: "Drow"
class:
 - "Drow Mage"
subClass:
 - "CR 3"
cover: "Drow Navigator.jpg"
campaign: "THE DROWNED CROWN"
locations:
  - "[[Drow Warship]]"
tags:
  - race/drow
  - affinity/hostile
  - campaign/theDrownedCrown
---
###### Drow Navigator
:FasPerson: Enemy &nbsp; | &nbsp; :FasMapLocationDot: [[Drow Warship]]
___

> [!infobox|no-t right]
> ![[Drow Navigator.jpg]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Drow Mage |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Drow |

> [!quote|no-t]
> The navigator of the Drow patrol ship — knows the exact location of the crown. A key **capture target**. Will attempt to flee or bargain before fighting, but is capable in a pinch.

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 18 | 12 | 14 | 12 | 10 |
| **Mod** | -1 | +4 | +1 | +2 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 13
**Languages:** Elvish, Undercommon, Common
**Skills:** Arcana +4, Perception +3, Stealth +6

---

### Traits

**Fey Ancestry.** Advantage on saves vs. charm; immune to magical sleep.
**Innate Spellcasting** (Charisma, spell save DC 11):
- At will: *dancing lights*
- 1/day each: *darkness, faerie fire*

**Navigator's Charts.** Advantage on Wisdom (Survival) checks to navigate at sea.

**Sunlight Sensitivity.** Disadvantage on attack rolls and Perception checks that rely on sight in sunlight.

---

### Actions

**Shortsword.** *Melee:* +6 to hit, reach 5 ft. *Hit:* 7 (1d6 + 4) piercing.

**Hand Crossbow.** *Ranged:* +6 to hit, range 30/120 ft. *Hit:* 7 (1d6 + 4) piercing + DC 12 Con save or poisoned for 1 hour.

**Spellcasting.** Intelligence, spell save DC 12, +4 to hit. Slots: 1st ×4, 2nd ×2.
- 1st: *fog cloud, mage armor, magic missile*
- 2nd: *hold person, misty step*

---

### Reactions

**Misty Escape** (1/day). When reduced to 0 HP, before falling unconscious the navigator casts *misty step* to teleport up to 30 ft. to a space they can see.

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
