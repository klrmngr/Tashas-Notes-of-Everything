---
type: pc
race: "Undead"
class:
 - "Poltergeist"
subClass:
 - "CR 2"
cover: "Poltergeist.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/2
  - source/mm
---
###### Poltergeist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Poltergeist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 14 | 11 | 10 | 10 | 11 |
| **Mod** | -5 | +2 | +0 | +0 | +0 | +0 |

**Speed:** 0 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands all languages it knew in life but can't speak
**Damage Resistances:** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Incorporeal Movement.** The poltergeist can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Sunlight Sensitivity.** While in sunlight, the poltergeist has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Invisibility.** The poltergeist is invisible.


---

### Actions

**Forceful Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 10 (3d6) force damage.

**Telekinetic Thrust.** The poltergeist targets a creature or unattended object within 30 feet of it. A creature must be Medium or smaller to be affected by this magic, and an object can weigh up to 150 pounds.
If the target is a creature, the poltergeist makes a Charisma check contested by the target's Strength check. If the poltergeist wins the contest, the poltergeist hurls the target up to 30 feet in any direction, including upward. If the target then comes into contact with a hard surface or heavy object, the target takes 1d6 damage per 10 feet moved.
If the target is an object that isn't being worn or carried, the poltergeist hurls it up to 30 feet in any direction. The poltergeist can use the object as a ranged weapon, attacking one creature along the object's path (+4 to hit) and dealing 5 (2d4) bludgeoning damage on a hit.


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