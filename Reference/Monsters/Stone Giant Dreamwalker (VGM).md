---
type: pc
race: "Giant (stone giant)"
class:
 - "Stone Giant Dreamwalker"
subClass:
 - "CR 10"
cover: "Stone Giant Dreamwalker.png"
campaign:
locations:
tags:
  - race/stone giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/10
  - source/vgm
---
###### Stone Giant Dreamwalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Stone Giant Dreamwalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Giant (stone giant) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 161 (14d12 + 70) |
> | :FasUserGroup: Race | Giant (stone giant) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 14 | 21 | 10 | 8 | 12 |
| **Mod** | +6 | +2 | +5 | +0 | -1 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Giant
**Saving Throws:** Dex +6, Con +9, Wis +3
**Skills:** Athletics +14, Perception +3
**Condition Immunities:** charmed; frightened

---

### Traits

**Dreamwalker's Charm.** An enemy that starts its turn within 30 feet of the giant must make a DC 13 Charisma saving throw, provided that the giant isn't incapacitated. On a failed save, the creature is charmed by the giant. A creature charmed in this way can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. Once it succeeds on the saving throw, the creature is immune to this giant's Dreamwalker's Charm for 24 hours.


---

### Actions

**Multiattack.** The giant makes two attacks with its greatclub.

**Greatclub.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage.

**Petrifying Touch.** The giant touches one Medium or smaller creature within 10 feet of it that is charmed by it. The target must make a DC 17 Constitution saving throw. On a failed save, the target becomes petrified, and the giant can adhere the target to its stony body. Greater restoration spells and other magic that can undo petrification have no effect on a petrified creature on the giant unless the giant is dead, in which case the magic works normally, freeing the petrified creature as well as ending the petrified condition on it.

**Rock.** Ranged Weapon Attack: +10 to hit, range 60/240 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or be knocked prone.


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