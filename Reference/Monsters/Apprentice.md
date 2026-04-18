---
type: pc
race: "Humanoid"
class:
 - "Apprentice"
subClass:
 - "CR —"
cover: "Apprentice.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/hol
---
###### Apprentice
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HoL
___

> [!infobox|no-t right]
> ![[Apprentice.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 7 (2d8 - 2) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | HoL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 10 | 9 | 13 | 11 | 12 |
| **Mod** | -1 | +0 | -1 | +1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** any one language (usually Common)
**Saving Throws:** Int +3
**Skills:** Arcana +3, History +3

---

### Actions

**Quarterstaff.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two hands.

**Burning Hands (1st-Level Spell; 2/Day).** You shoot forth a 15-foot cone of fire. Each creature in that area must make a DC 11 Dexterity saving throw. A creature takes 10 (3d6) fire damage on a failed save, or half as much damage on a successful one The fire ignites any flammable objects in the area that aren't being worn or carried.

**Fire Bolt (Cantrip).** Ranged Spell Attack: Ranged Spell Attack: +3 to hit, range 120 ft., one target. *Hit:* 5 (1d10) fire damage. A flammable object hit by this spell ignites if it isn't being worn or carried.


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