---
type: pc
race: "Swarm of Tiny Beasts"
class:
 - "Swarm of Scarabs"
subClass:
 - "CR 3"
cover: "Swarm of Scarabs.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/3
  - source/vrgr
---
###### Swarm of Scarabs
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Swarm of Scarabs.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Beasts |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Swarm of Tiny Beasts |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 14 | 13 | 1 | 12 | 1 |
| **Mod** | -4 | +2 | +1 | -5 | +1 | -5 |

**Speed:** 30 ft., burrow 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** tremorsense 60 ft., passive Perception 11
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny scarab. The swarm can't regain hit points or gain temporary hit points.

**Skeletonize.** If the swarm starts its turn in the same space as a dead creature that is Large or smaller, the corpse is destroyed, leaving behind only equipment and bones (or exoskeleton).

**Spider Climb.** The swarm can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Ravenous Bites.** Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 14 (4d6) piercing damage, or 7 (2d6) piercing damage if the swarm has half of its hit points or fewer. If the target is a creature, scarabs burrow into its body, and the creature takes 3 (1d6) piercing damage at the start of each of its turns. Any creature can use an action to kill or remove the scarabs with fire or a weapon that deals piercing damage, causing 1 damage of the appropriate type to the target. A creature reduced to 0 hit points by the swarm's piercing damage dies.


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