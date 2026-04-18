---
type: pc
race: "Aberration"
class:
 - "Gazer"
subClass:
 - "CR 1/2"
cover: "Gazer.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/1-2
  - source/vgm
---
###### Gazer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Gazer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Tiny Aberration |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 13 (3d4 + 6) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 17 | 14 | 3 | 10 | 7 |
| **Mod** | -4 | +3 | +2 | -4 | +0 | -2 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** —
**Saving Throws:** Wis +2
**Skills:** Perception +4, Stealth +5
**Condition Immunities:** prone

---

### Traits

**Aggressive.** As a bonus action, the gazer can move up to its speed toward a hostile creature that it can see.

**Mimicry.** The gazer can mimic simple sounds of speech it has heard, in any language. A creature that hears the sounds can tell they are imitations with a successful DC 10 Wisdom (Insight) check.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage.

**Eye Rays.** The gazer shoots two of the following magical eye rays at random (reroll duplicates), choosing one or two targets it can see within 60 feet of it:
- The targeted creature must succeed on a DC 12 Wisdom saving throw or be charmed until the start of the gazer's next turn. While the target is charmed in this way, its speed is halved, and it has disadvantage on attack rolls.
- The targeted creature must succeed on a DC 12 Wisdom saving throw or be frightened until the start of the gazer's next turn.
- The targeted creature must succeed on a DC 12 Dexterity saving throw or take 10 (3d6) cold damage.
- If the target is a creature that is Medium or smaller, it must succeed on a DC 12 Strength saving throw or be moved up to 30 feet directly away from the gazer.
- If the target is an object weighing 10 pounds or less that isn't being worn or carried, the gazer moves it up to 30 feet in any direction. The gazer can also exert fine control on objects with this ray, such as manipulating a simple tool or opening a container.


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