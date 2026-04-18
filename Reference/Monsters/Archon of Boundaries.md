---
type: pc
race: "Celestial"
class:
 - "Archon of Boundaries"
subClass:
 - "CR 15"
cover: "Archon of Boundaries.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/huge
  - cr/15
  - source/mcv4ec
---
###### Archon of Boundaries
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Archon of Boundaries.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Celestial |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 195 (17d12 + 85) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 17 | 20 | 14 | 18 | 18 |
| **Mod** | +6 | +3 | +5 | +2 | +4 | +4 |

**Speed:** 60 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 19
**Languages:** understands Common and Celestial but can't speak
**Saving Throws:** Con +10, Wis +9
**Skills:** Insight +9, Perception +9
**Damage Resistances:** radiant
**Condition Immunities:** exhaustion

---

### Traits

**Legendary Resistance (3/Day).** If the archon fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The archon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The archon makes one Hooves attack and one Radiant Lance attack.

**Hooves.** Melee Weapon Attack: +11 to hit, reach 5 ft., one target. *Hit:* 20 (4d6 + 6) bludgeoning damage plus 10 (3d6) radiant damage. If the target is a Medium or smaller creature, it must succeed on a DC 19 Strength saving throw or have the prone condition.

**Radiant Lance.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 12 (1d12 + 6) piercing damage plus 28 (8d6) radiant damage, and the target is marked until the start of the archon's next turn. While it is marked, the target has disadvantage on attack rolls against creatures other than the archon.


---

### Reactions

**Archon's Pursuit.** When a creature marked by the archon's Radiant Lance ends its turn within 120 feet of the archon, the archon teleports to an unoccupied space it can see within 5 feet of the creature.

**Haunting Radiance.** Immediately after a creature within 120 feet of the archon forces it to make a saving throw, the archon responds with a burst of light. The creature must succeed on a DC 17 Constitution saving throw or have the blinded condition until the end of the creature's next turn.

**Parry.** The archon adds 5 to its AC against one melee attack that would hit it, provided it can see the attacker.


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