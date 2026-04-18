---
type: pc
race: "Drow"
class:
 - "Drow Elite Warrior"
subClass:
 - "CR 5"
cover: "Drow Lieutenant.png"
campaign: "THE DROWNED CROWN"
locations:
  - "[[Drow Warship]]"
tags:
  - race/drow
  - affinity/hostile
  - campaign/theDrownedCrown
---
###### Drow Lieutenant
:FasPerson: Enemy &nbsp; | &nbsp; :FasMapLocationDot: [[Drow Warship]]
___

> [!infobox|no-t right]
> ![[Drow Lieutenant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Drow Elite Warrior |
> | :FasShield: AC | 18 (studded leather + shield) |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Drow |

> [!quote|no-t]
> Commands the Drow patrol ship that intercepts the party mid-journey. Disciplined, ruthless, and experienced in shipboard combat — will fight to the death before surrendering.

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 14 | 11 | 13 | 12 |
| **Mod** | +1 | +4 | +2 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 14
**Languages:** Elvish, Undercommon
**Saving Throws:** Dex +7, Con +5, Wis +4
**Skills:** Perception +4, Stealth +10

---

### Traits

**Fey Ancestry.** Advantage on saves vs. charm; immune to magical sleep.
**Innate Spellcasting** (Charisma, spell save DC 12):
- At will: *dancing lights*
- 1/day each: *darkness, faerie fire*

**Sunlight Sensitivity.** Disadvantage on attack rolls and Perception checks that rely on sight in sunlight.

---

### Actions

**Multiattack.** Two shortsword attacks.

**Shortsword.** *Melee:* +7 to hit, reach 5 ft. *Hit:* 7 (1d6 + 4) piercing.

**Hand Crossbow.** *Ranged:* +7 to hit, range 30/120 ft. *Hit:* 7 (1d6 + 4) piercing + DC 13 Con save or 10 (3d6) poison damage and poisoned for 1 hour.

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
