---
type: pc
race: "Swarm of Tiny Constructs"
class:
 - "Swarm of Books"
subClass:
 - "CR 1/4"
cover: "Swarm of Books.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-4
  - source/wdh
---
###### Swarm of Books
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Swarm of Books.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Constructs |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Swarm of Tiny Constructs |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 5 | 15 | 10 | 2 | 12 | 4 |
| **Mod** | -3 | +2 | +0 | -4 | +1 | -3 |

**Speed:** 0 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 11
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; paralyzed; petrified; prone; restrained; stunned; grappled

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny book. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Slam.** Melee Weapon Attack: +4 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 5 (2d4) bludgeoning damage, or 2 (1d4) bludgeoning damage if the swarm has half of its hit points or fewer.


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