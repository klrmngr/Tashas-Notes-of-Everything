---
type: pc
race: "Aberration"
class:
 - "Eyedrake"
subClass:
 - "CR 8"
cover: "Eyedrake.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/8
  - source/ftd
---
###### Eyedrake
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Eyedrake.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 119 (14d10 + 42) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 16 | 14 | 14 | 16 |
| **Mod** | +3 | +0 | +3 | +2 | +2 | +3 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** Deep Speech, Draconic
**Saving Throws:** Con +6, Wis +5
**Skills:** Perception +8, Stealth +6
**Condition Immunities:** prone

---

### Traits

**Unusual Nature.** The eyedrake doesn't require food or drink.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 13 (3d6 + 3) piercing damage.

**Antimagic Breath (Recharge 6).** The eyedrake emits a magic wave in a 30-foot cone. Each creature in that area must make a DC 14 Constitution saving throw, taking 39 (6d12) force damage on a failed save, or half as much damage on a successful one. Every spell of 3rd level or lower ends on creatures and objects of the eyedrake's choice in that area.

**Eye Rays.** The eyedrake shoots three of the following magical eye rays at random (reroll duplicates), each ray targeting one creature it can see within 60 feet of it:
- **1: Freezing Ray.** The target must make a DC 14 Constitution saving throw. On a failed save, the target takes 17 (5d6) cold damage, and its speed is halved until the end of its next turn. On a successful save, the target takes half as much damage with no additional effects.
- **2: Debilitating Ray.** The target must succeed on a DC 14 Constitution saving throw or take 7 (2d6) thunder damage and become incapacitated until the end of its next turn.
- **3: Repulsion Ray.** The target must succeed on a DC 14 Strength saving throw or take 14 (4d6) force damage and be pushed up to 60 feet away from the eyedrake.
- **4: Fire Ray.** The target must make a DC 14 Dexterity saving throw, taking 21 (6d6) fire damage on a failed save, or half as much damage on a successful one.
- **5: Paralyzing Ray.** The target must succeed on a DC 14 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- **6: Death Ray.** The target must make a DC 14 Dexterity saving throw, taking 28 (8d6) necrotic damage on a failed save, or half as much damage on a successful one. The target dies if the ray reduces it to 0 hit points.


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