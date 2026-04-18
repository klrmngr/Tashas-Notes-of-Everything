---
type: pc
race: "Humanoid (sorcerer)"
class:
 - "Occult Silvertongue"
subClass:
 - "CR 8"
cover: "Occult Silvertongue.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/crcotn
---
###### Occult Silvertongue
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Occult Silvertongue.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (sorcerer) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 127 (17d8 + 51) |
> | :FasUserGroup: Race | Humanoid (sorcerer) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 16 | 15 | 17 | 20 |
| **Mod** | +1 | +3 | +3 | +2 | +3 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 16
**Languages:** Common plus three other languages, telepathy 60 ft.
**Saving Throws:** Wis +6, Cha +8
**Skills:** Arcana +8, Deception +11, History +5, Perception +6
**Damage Resistances:** psychic

---

### Traits

**Alien Mind.** If a creature tries to read the silvertongue's thoughts or deals psychic damage to the silvertongue, that creature must succeed on a DC 16 Intelligence saving throw or be stunned until the start of its next turn.

**Magic Resistance.** The silvertongue has advantage on saving throws against spells and other magical effects.


---

### Actions

**Crimson Bolt.** Melee or Ranged Spell Attack: +8 to hit, reach 5 ft. or range 60 ft., one creature. *Hit:* 27 (4d10 + 5) psychic damage.


---

### Bonus Actions

**Elemental Servitor (1/Day).** The silvertongue magically summons an earth elemental, which appears in an unoccupied space the silvertongue can see within 60 feet of itself. The earth elemental takes its turn immediately after the silvertongue on the same initiative count and obeys the silvertongue's commands. The earth elemental disappears after 1 minute or when it or the silvertongue dies.


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