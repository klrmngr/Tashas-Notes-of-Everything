---
type: pc
race: "Undead"
class:
 - "Death Tyrant"
subClass:
 - "CR 14"
cover: "Death Tyrant.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/14
  - source/mm
---
###### Death Tyrant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Death Tyrant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 187 (25d10 + 50) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 14 | 19 | 15 | 19 |
| **Mod** | +0 | +2 | +2 | +4 | +2 | +4 |

**Speed:** 0 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 22
**Languages:** Deep Speech, Undercommon
**Saving Throws:** Str +5, Con +7, Int +9, Wis +7, Cha +9
**Skills:** Perception +12
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; paralyzed; petrified; poisoned; prone

---

### Traits

**Negative Energy Cone.** The death tyrant's central eye emits an invisible, magical 150-foot cone of negative energy. At the start of each of its turns, the tyrant decides which way the cone faces and whether the cone is active.
Any creature in that area can't regain hit points. Any humanoid that dies there becomes a zombie under the tyrant's command. The dead humanoid retains its place in the initiative order and animates at the start of its next turn, provided that its body hasn't been completely destroyed.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 14 (4d6) piercing damage.

**Eye Rays.** The death tyrant shoots three of the following magical eye rays at random (reroll duplicates), choosing one to three targets it can see within 120 feet of it:
- The targeted creature must succeed on a DC 17 Wisdom saving throw or be charmed by the death tyrant for 1 hour, or until the death tyrant harms the creature.
- The targeted creature must succeed on a DC 17 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- The targeted creature must succeed on a DC 17 Wisdom saving throw or be frightened for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- The targeted creature must succeed on a DC 17 Dexterity saving throw. On a failed save, the target's speed is halved for 1 minute. In addition, the creature can't take reactions, and it can take either an action or a bonus action on its turn, not both. The creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.
- The targeted creature must make a DC 17 Constitution saving throw, taking 36 (8d8) necrotic damage on a failed save, or half as much damage on a successful one.
- If the target is a creature, it must succeed on a DC 17 Strength saving throw or the death tyrant moves it up to 30 feet in any direction. It is restrained by the ray's telekinetic grip until the start of the death tyrant's next turn or until the death tyrant is incapacitated.
- If the target is an object weighing 300 pounds or less that isn't being worn or carried, it is moved up to 30 feet in any direction. The death tyrant can also exert fine control on objects with this ray, such as manipulating a simple tool or opening a door or a container.
- The targeted creature must succeed on a DC 17 Wisdom saving throw or fall asleep and remain unconscious for 1 minute. The target awakens if it takes damage or another creature takes an action to wake it. This ray has no effect on constructs and undead.
- The targeted creature must make a DC 17 Dexterity saving throw. On a failed save, the creature begins to turn to stone and is restrained. It must repeat the saving throw at the end of its next turn. On a success, the effect ends. On a failure, the creature is petrified until freed by the  greater restoration spell or other magic.
- If the target is a creature, it must succeed on a DC 17 Dexterity saving throw or take 45 (10d8) force damage. If this damage reduces the creature to 0 hit points, its body becomes a pile of fine gray dust.
- If the target is a Large or smaller nonmagical object or creation of magical force, it is disintegrated without a saving throw. If the target is a Huge or larger object or creation of magical force, this ray disintegrates a 10-foot cube of it.
- The targeted creature must succeed on a DC 17 Dexterity saving throw or take 55 (10d10) necrotic damage. The target dies if the ray reduces it to 0 hit points.


---

### Legendary Actions

### 

**Eye Ray.** The death tyrant uses one random eye ray.


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