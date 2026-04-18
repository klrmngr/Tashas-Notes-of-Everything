---
type: pc
race: "Swarm of Tiny Aberrations"
class:
 - "Neogi Hatchling Swarm"
subClass:
 - "CR 3"
cover: "Neogi Hatchling Swarm.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/3
  - source/bam
---
###### Neogi Hatchling Swarm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Neogi Hatchling Swarm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Aberrations |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Swarm of Tiny Aberrations |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 13 | 14 | 6 | 10 | 9 |
| **Mod** | +1 | +1 | +2 | -2 | +0 | -1 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Spider Climb.** The swarm can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny neogi hatchling. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Swarm of Bites.** Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. *Hit:* 22 (6d6 + 1) poison damage, or 11 (3d6 + 1) poison damage if the swarm has half of its hit points or fewer, and the target must succeed on a DC 12 Constitution saving throw or become poisoned for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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