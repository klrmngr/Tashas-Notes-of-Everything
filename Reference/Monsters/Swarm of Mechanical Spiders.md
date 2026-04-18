---
type: pc
race: "Swarm of Tiny Constructs"
class:
 - "Swarm of Mechanical Spiders"
subClass:
 - "CR 1/2"
cover: "Swarm of Mechanical Spiders.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-2
  - source/wdh
---
###### Swarm of Mechanical Spiders
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Swarm of Mechanical Spiders.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Constructs |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Swarm of Tiny Constructs |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 13 | 10 | 1 | 7 | 1 |
| **Mod** | -4 | +1 | +0 | -5 | -2 | -5 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., passive Perception 8
**Languages:** —
**Damage Vulnerabilities:** lightning
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** exhaustion; charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned; poisoned

---

### Traits

**Constructed Nature.** The swarm doesn't require air, food, drink, or sleep.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny insect. The swarm can't regain hit points or gain temporary hit points.

**Spider Climb.** The swarm can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** While in contact with a web, the swarm knows the exact location of any other creature in contact with the same web.

**Web Walker.** The swarm ignores movement restrictions caused by webbing.


---

### Actions

**Bites.** Melee Weapon Attack: +3 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 10 (4d4) piercing damage, or 5 (2d4) piercing damage if the swarm has half of its hit points or fewer.


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