---
type: pc
race: "Elemental"
class:
 - "Mud Hulk"
subClass:
 - "CR 3"
cover: "Mud Hulk.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/3
  - source/bgg
---
###### Mud Hulk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Mud Hulk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 8 | 16 | 5 | 9 | 6 |
| **Mod** | +3 | -1 | +3 | -3 | -1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** Giant, Terran
**Damage Resistances:** acid
**Condition Immunities:** exhaustion; paralyzed

---

### Traits

**Amorphous.** The mud hulk can move through a space as narrow as 1 inch without squeezing.

**Sticky Mud.** The ground within 15 feet of the mud hulk is difficult terrain for other creatures.


---

### Actions

**Enveloping Slam.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 9 (1d12 + 3) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 13 Strength saving throw or be pulled into the mud hulk's space and be engulfed by the mud hulk. While engulfed, the target can't breathe, has the restrained condition, and takes 6 (1d12) acid damage at the start of each of its turns. When the mud hulk moves, the engulfed target moves with it. The mud hulk can have only one target engulfed at a time. While a creature is engulfed, the mud hulk can't use its Amorphous trait.
An engulfed target can repeat the saving throw at the end of each of its turns. On a successful save, the target escapes and enters the nearest unoccupied space.

**Mud Splash.** The mud hulk lobs a mass of mud that splashes in a 10-foot-radius sphere centered on a point within 30 feet of the mud hulk. Each creature in that area must make a DC 13 Dexterity saving throw, taking 10 (2d6 + 3) bludgeoning damage on a failed save, or half as much damage on a successful one. The affected area is difficult terrain until the start of the mud hulk's next turn.


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