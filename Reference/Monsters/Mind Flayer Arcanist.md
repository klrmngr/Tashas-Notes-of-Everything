---
type: pc
race: "Aberration"
class:
 - "Mind Flayer Arcanist"
subClass:
 - "CR 8"
cover: "Mind Flayer Arcanist.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/8
  - source/mm
---
###### Mind Flayer Arcanist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Mind Flayer Arcanist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (breastplate) |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 12 | 19 | 17 | 17 |
| **Mod** | +0 | +1 | +1 | +4 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Deep Speech, Undercommon, telepathy 120 ft.
**Saving Throws:** Int +7, Wis +6, Cha +6
**Skills:** Arcana +7, Deception +6, Insight +6, Perception +6, Persuasion +6, Stealth +4

---

### Traits

**Magic Resistance.** The mind flayer has advantage on saving throws against spells and other magical effects.


---

### Actions

**Tentacles.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 15 (2d10 + 4) psychic damage. If the target is Medium or smaller, it is grappled (escape DC 15) and must succeed on a DC 15 Intelligence saving throw or be stunned until this grapple ends.

**Extract Brain.** Melee Weapon Attack: +7 to hit, reach 5 ft., one incapacitated humanoid grappled by the mind flayer. *Hit:* The target takes 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the mind flayer kills the target by extracting and devouring its brain.

**Mind Blast (Recharge 5–6).** The mind flayer magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 15 Intelligence saving throw or take 22 (4d8 + 4) psychic damage and be stunned for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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