---
type: pc
race: "Construct"
class:
 - "Warforged Colossus"
subClass:
 - "CR 25"
cover: "Warforged Colossus.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/gargantuan
  - cr/25
  - source/erlw
---
###### Warforged Colossus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Warforged Colossus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Gargantuan Construct |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 23 (natural armor) |
> | :FasHeart: HP | 410 (20d20 + 200) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 11 | 30 | 3 | 11 | 8 |
| **Mod** | +10 | +0 | +10 | -4 | +0 | -1 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** truesight 150 ft., passive Perception 10
**Languages:** understands Common but can't speak
**Saving Throws:** Int +4, Wis +8, Cha +7
**Damage Immunities:** necrotic; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; incapacitated; paralyzed; petrified; poisoned; stunned

---

### Traits

**Immutable Form.** The colossus is immune to any spell or effect that would alter its form.

**Legendary Resistance (3/Day).** If the colossus fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The colossus has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The colossus deals double damage to objects and structures.

**Towering Terror.** Any enemy outside the colossus that starts its turn within 30 feet of it must succeed on a DC 26 Wisdom saving throw or be frightened until the start of the enemy's next turn. If the enemy's saving throw is successful, it is immune to this colossus's Towering Terror for the next 24 hours.


---

### Actions

**Multiattack.** The colossus makes three attacks—one with its slam and two with its eldritch turrets—and then uses Stomp.

**Slam.** Melee Weapon Attack: +18 to hit, reach 20 ft., one target. *Hit:* 29 (3d12 + 10) bludgeoning damage, and the colossus can push the target up to 20 feet away from it.

**Eldritch Turret.** Ranged Spell Attack: +18 to hit, range 300 ft., one target. *Hit:* 18 (4d8) force damage, and if the target is a creature, it is knocked prone.

**Stomp.** The colossus stomps one of its feet at a point on the ground within 20 feet of it. Any creature in a 20-foot-radius, 20-foot-high cylinder centered on this point must succeed on a DC 26 Dexterity saving throw or take 33 (6d10) bludgeoning damage and fall prone. Until the colossus uses its Stomp again or moves, the creature is restrained. While restrained in this way, the creature (or another creature within 5 feet of it) can use its action to make a DC 26 Strength check. On a success, the creature relocates to an unoccupied space of its choice within 5 feet of the colossus and is no longer restrained.
Structures, as well as nonmagical objects that are neither being worn nor carried, take the same amount of damage if they are in the cylinder (no save).

**Incinerating Beam (Recharge 5–6).** The colossus fires a beam of light in a 150-foot line that is 10 feet wide. Each creature in the line must make a DC 26 Dexterity saving throw, taking 60 (11d10) radiant damage on a failed save, or half as much damage on a successful one. A creature reduced to 0 hit points by this beam is disintegrated, leaving behind anything it was wearing or carrying.


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