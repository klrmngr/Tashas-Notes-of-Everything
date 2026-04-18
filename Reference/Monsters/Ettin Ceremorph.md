---
type: pc
race: "Aberration"
class:
 - "Ettin Ceremorph"
subClass:
 - "CR 8"
cover: "Ettin Ceremorph.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/8
  - source/bgg
---
###### Ettin Ceremorph
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Ettin Ceremorph.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 104 (11d10 + 44) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 18 | 15 | 14 |
| **Mod** | +4 | +2 | +4 | +4 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Deep Speech, Giant, telepathy 60 ft., Undercommon
**Saving Throws:** Int +7, Wis +5
**Skills:** Perception +8
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened; stunned; unconscious

---

### Traits

**Magic Resistance.** The ceremorph has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The ceremorph makes one Slam attack and one Tentacles attack. The ceremorph can replace one of the attacks with a Mind Bolt attack, if available.

**Slam.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 22 (4d8 + 4) bludgeoning damage.

**Tentacles.** Melee Weapon Attack: +7 to hit, reach 10 ft., one creature. *Hit:* 15 (2d10 + 4) psychic damage. If the target is Large or smaller, it has the grappled condition (escape DC 14) and must succeed on a DC 15 Intelligence saving throw or have the stunned condition until this grapple ends.

**Extract Brain.** Melee Weapon Attack: +7 to hit, reach 5 ft., one incapacitated Humanoid grappled by the ceremorph. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the ceremorph kills the target by extracting and devouring its brain.

**Mind Bolt (3/Day).** Ranged Spell Attack: +7 to hit, range 120 ft., one creature. *Hit:* 17 (2d12 + 4) psychic damage, and the target must succeed on a DC 15 Intelligence saving throw or have the stunned condition until the end of its next turn.


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