---
type: pc
race: "Construct"
class:
 - "Retriever"
subClass:
 - "CR 14"
cover: "Retriever.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/14
  - source/mpmm
---
###### Retriever
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Retriever.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 210 (20d10 + 100) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 16 | 20 | 3 | 11 | 4 |
| **Mod** | +6 | +3 | +5 | -4 | +0 | -3 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 60 ft., passive Perception 15
**Languages:** understands Abyssal, Elvish, and Undercommon but can't speak
**Saving Throws:** Dex +8, Con +10, Wis +5
**Skills:** Perception +5, Stealth +8
**Damage Immunities:** necrotic; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Faultless Tracker.** The retriever is given a quarry by its master. The quarry can be a specific creature or object the master is personally acquainted with, or it can be a general type of creature or object the master has seen before. The retriever knows the direction and distance to its quarry as long as the two of them are on the same plane of existence. The retriever can have only one such quarry at a time. The retriever also always knows the location of its master.


---

### Actions

**Multiattack.** The retriever makes two Foreleg attacks, and it uses Force Beam or Paralyzing Beam, if available.

**Foreleg.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) slashing damage.

**Force Beam.** The retriever targets one creature it can see within 60 feet of it. The target must make a DC 16 Dexterity saving throw, taking 27 (5d10) force damage on a failed save, or half as much damage on a successful one.

**Paralyzing Beam (Recharge 5–6).** The retriever targets one creature it can see within 60 feet of it. The target must succeed on a DC 18 Constitution saving throw or be paralyzed for 1 minute. The paralyzed target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
If the paralyzed creature is Medium or smaller, the retriever can pick it up as part of the retriever's move and walk or climb with it at full speed.


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