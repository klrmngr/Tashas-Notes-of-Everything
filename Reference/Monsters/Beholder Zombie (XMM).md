---
type: pc
race: "Undead"
class:
 - "Beholder Zombie"
subClass:
 - "CR 5"
cover: "Beholder Zombie.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/5
  - source/xmm
---
###### Beholder Zombie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Beholder Zombie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 8 | 16 | 3 | 8 | 5 |
| **Mod** | +2 | -1 | +3 | -4 | -1 | -3 |

**Speed:** 5 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 9
**Languages:** understands Deep Speech and Undercommon but can't speak
**Saving Throws:** Wis +2
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned; prone

---

### Traits

**Undead Fortitude.** If damage reduces the zombie to 0 Hit Points, it makes a Constitution saving throw (DC 5 plus the damage taken) unless the damage is Radiant or from a Critical Hit. On a successful save, the zombie drops to 1 Hit Point instead.


---

### Actions

**Multiattack.** The zombie uses Eye Rays twice.

**Bite.** m +5, reach 5 ft. *Hit:* 16 (4d6 + 2) Piercing damage.

**Eye Rays.** The zombie randomly shoots one of the following magical rays at a target it can see within 120 feet of itself (roll 1d4; reroll if the zombie has already used that ray during this turn):
- **1: Paralyzing Ray.** con DC 14.  The target has the Paralyzed condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
- **2: Fear Ray.** wis DC 14.  13 (3d8) Psychic damage, and the target has the Frightened condition until the end of its next turn.
- **3: Enervation Ray.** con DC 14.  10 (3d6) Necrotic damage, and the target has the Poisoned condition until the end of its next turn. While Poisoned, the target can't regain Hit Points.  Half damage only.
- **4: Disintegration Ray.** dex DC 14.  27 (5d10) Force damage. If the target is a nonmagical object or a creation of magical force, a 10-foot Cube of it disintegrates into dust.  Half damage.  If the target is a creature and this damage reduces it to 0 Hit Points, it disintegrates into dust.


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