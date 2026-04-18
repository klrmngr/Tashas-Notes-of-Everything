---
type: pc
race: "Swarm of Tiny Undeads"
class:
 - "Swarm of Zombie Limbs"
subClass:
 - "CR 1"
cover: "Swarm of Zombie Limbs.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1
  - source/vrgr
---
###### Swarm of Zombie Limbs
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Swarm of Zombie Limbs.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Undeads |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Swarm of Tiny Undeads |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 10 | 3 | 8 | 5 |
| **Mod** | +2 | +0 | +0 | -4 | -1 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 9
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny limb. The swarm can't regain hit points or gain temporary hit points.

**Unusual Nature.** The swarm doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The swarm makes one Undead Mass attack and one Grasping Limbs attack.

**Undead Mass.** Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 5 (1d6 + 2) bludgeoning damage, or 4 (1d4 + 2) bludgeoning damage if the swarm has half of its hit points or fewer.

**Grasping Limbs.** Melee Weapon Attack: +4 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 7 (2d6) necrotic damage, and the creature must succeed on a DC 12 Strength saving throw or be restrained. The creature can repeat the saving throw at the end of each of its turns, taking 7 (2d6) necrotic damage on a failed save. The creature is freed if it succeeds on this saving throw, the swarm moves out of the creature's space, or the swarm dies.


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