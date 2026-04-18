---
type: pc
race: "Swarm of Medium Undeads"
class:
 - "Skeletal Swarm"
subClass:
 - "CR 2"
cover: "Skeletal Swarm.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/2
  - source/gos
---
###### Skeletal Swarm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Skeletal Swarm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Swarm of Medium Undeads |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (armor scraps) |
> | :FasHeart: HP | 60 (8d10 + 16) |
> | :FasUserGroup: Race | Swarm of Medium Undeads |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 15 | 6 | 8 | 5 |
| **Mod** | +1 | +2 | +2 | -2 | -1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** —
**Damage Vulnerabilities:** bludgeoning
**Damage Resistances:** slashing; piercing
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Deafening Clatter.** Creatures are deafened while in the swarm's space.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Small humanoid. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Slash.** Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 11 (2d8 + 2) slashing damage, or 6 (1d8 + 2) slashing damage if the swarm has half of its hit points or fewer.


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