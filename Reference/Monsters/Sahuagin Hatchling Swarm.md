---
type: pc
race: "Swarm of Tiny Beasts"
class:
 - "Sahuagin Hatchling Swarm"
subClass:
 - "CR 3"
cover: "Sahuagin Hatchling Swarm.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/3
  - source/gos
---
###### Sahuagin Hatchling Swarm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Sahuagin Hatchling Swarm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Swarm of Tiny Beasts |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 52 (8d10 + 8) |
> | :FasUserGroup: Race | Swarm of Tiny Beasts |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 18 | 12 | 3 | 10 | 3 |
| **Mod** | -1 | +4 | +1 | -4 | +0 | -4 |

**Speed:** 0 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Blood Frenzy.** The swarm has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Seething.** Once it enters combat, the swarm deals 10 slashing damage to itself at the end of its turn if it did not make an attack on that turn. This damage ignores resistance, and it cannot reduce the swarm to 0 hit points.

**Swarm.** The swarm can occupy another creature's space and vice versa, and it can move through any opening large enough for a Tiny creature. The swarm can't regain hit points or gain temporary hit points.

**Water Breathing.** The swarm can breathe only underwater.


---

### Actions

**Bites.** Melee Weapon Attack: +6 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 14 (4d6) piercing damage, or 7 (2d6) piercing damage if the swarm has half of its hit points or fewer.


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