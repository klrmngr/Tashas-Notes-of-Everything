---
type: pc
race: "Aberration"
class:
 - "Neothelid"
subClass:
 - "CR 13"
cover: "Neothelid.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/gargantuan
  - cr/13
  - source/mpmm
---
###### Neothelid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Neothelid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Gargantuan Aberration |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 232 (15d20 + 75) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 7 | 21 | 3 | 16 | 12 |
| **Mod** | +8 | -2 | +5 | -4 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 13
**Languages:** —
**Saving Throws:** Int +1, Wis +8, Cha +6

---

### Traits

**Creature Sense.** The neothelid is aware of the presence of creatures within 1 mile of it that have an Intelligence score of 4 or higher. It knows the distance and direction to each creature, as well as each creature's Intelligence score, but can't sense anything else about it. A creature protected by a mind blank spell, a nondetection spell, or similar magic can't be perceived in this manner.

**Magic Resistance.** The neothelid has advantage on saving throws against spells and other magical effects.


---

### Actions

**Tentacles.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 21 (3d8 + 8) bludgeoning damage plus 11 (2d10) psychic damage. If the target is a Large or smaller creature, it must succeed on a DC 18 Strength saving throw or be swallowed by the neothelid. A swallowed creature is blinded and restrained, it has 3 against attacks and other effects outside the neothelid, and it takes 21 (6d6) acid damage at the start of each of the neothelid's turns.
If the neothelid takes 30 damage or more on a single turn from a creature inside it, the neothelid must succeed on a DC 18 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of the neothelid. If the neothelid dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting prone.

**Acid Breath (Recharge 5–6).** The neothelid exhales acid in a 60-foot cone. Each creature in that area must make a DC 18 Dexterity saving throw, taking 35 (10d6) acid damage on a failed save, or half as much damage on a successful one.


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