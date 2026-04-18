---
type: pc
race: "Aberration (mind flayer)"
class:
 - "Ulitharid"
subClass:
 - "CR 9"
cover: "Ulitharid.png"
campaign:
locations:
tags:
  - race/mind flayer
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/9
  - source/mpmm
---
###### Ulitharid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Ulitharid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Large Aberration (mind flayer) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (breastplate) |
> | :FasHeart: HP | 127 (17d10 + 14) |
> | :FasUserGroup: Race | Aberration (mind flayer) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 15 | 21 | 19 | 21 |
| **Mod** | +2 | +1 | +2 | +5 | +4 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Deep Speech, Undercommon, telepathy 2 miles
**Saving Throws:** Int +9, Wis +8, Cha +9
**Skills:** Arcana +9, Insight +8, Perception +8, Stealth +5

---

### Traits

**Creature Sense.** The ulitharid is aware of the presence of creatures within 2 miles of it that have an Intelligence score of 4 or higher. It knows the distance and direction to each creature, as well as each creature's intelligence score, but can't sense anything else about it. A creature protected by a mind blank spell, a nondetection spell, or similar magic can't be perceived in this manner.

**Magic Resistance.** The ulitharid has advantage on saving throws against spells and other magical effects.

**Psionic Hub.** If an elder brain establishes a psychic link with the ulitharid, the elder brain can form a psychic link with any other creature the ulitharid can detect using its Creature Sense. Any such link ends if the creature falls outside the telepathy ranges of both the ulitharid and the elder brain. The ulitharid can maintain its psychic link with the elder brain regardless of the distance between them, so long as they are both on the same plane of existence. If the ulitharid is more than 5 miles away from the elder brain, it can end the psychic link at any time (no action required).


---

### Actions

**Tentacles.** Melee Weapon Attack: +9 to hit, reach 10 ft., one creature. *Hit:* 27 (4d10 + 5) psychic damage. If the target is Large or smaller, it is grappled (escape DC 14) and must succeed on a DC 17 Intelligence saving throw or be stunned until this grapple ends.

**Extract Brain.** Melee Weapon Attack: +9 to hit, reach 5 ft., one incapacitated Humanoid grappled by the ulitharid. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the ulitharid kills the target by extracting and devouring its brain.

**Mind Blast (Recharge 5–6).** The ulitharid magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 17 Intelligence saving throw or take 31 (4d12 + 5) psychic damage and be stunned for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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