---
type: pc
race: "Aberration (beholder)"
class:
 - "Gazer"
subClass:
 - "CR 1/2"
cover: "Gazer.png"
campaign:
locations:
tags:
  - race/beholder
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/1-2
  - source/mpmm
---
###### Gazer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Gazer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Tiny Aberration (beholder) |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 13 (3d4 + 6) |
> | :FasUserGroup: Race | Aberration (beholder) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Mimicry.** The gazer can mimic simple sounds of speech it has heard, in any language. A creature that hears the sounds can tell they are imitations with a successful DC 10 Wisdom (Insight) check.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage.

**Eye Rays.** The gazer shoots two of the following magical eye rays at random (roll two d4s, and reroll duplicates), choosing one or two targets it can see within 60 feet of it:
- **1: Dazing Ray.** The targeted creature must succeed on a DC 12 Wisdom saving throw or be charmed until the start of the gazer's next turn. While the target is charmed in this way, its speed is halved, and it has disadvantage on attack rolls.
- **2: Fear Ray.** The targeted creature must succeed on a DC 12 Wisdom saving throw or be frightened until the start of the gazer's next turn.
- **3: Frost Ray.** The target must succeed on a DC 12 Dexterity saving throw or take 10 (3d6) cold damage.
- **4: Telekinetic Ray.** If the target is a creature that is Medium or smaller, it must succeed on a DC 12 Strength saving throw or be moved up to 30 feet directly away from the gazer. If the target is a Tiny object that isn't being worn or carried, the gazer moves it up to 30 feet in any direction. The gazer can also exert fine control on objects with this ray, such as manipulating a simple tool or opening a container.


---

### Bonus Actions

**Aggressive.** The gazer moves up to its speed toward a hostile creature that it can see.


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