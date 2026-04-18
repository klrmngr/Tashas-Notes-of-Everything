---
type: pc
race: "Swarm of Tiny Constructs"
class:
 - "Swarm of Animated Books"
subClass:
 - "CR 1/4"
cover: "Swarm of Animated Books.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-4
  - source/cm
---
###### Swarm of Animated Books
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Swarm of Animated Books.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Constructs |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Swarm of Tiny Constructs |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 12 | 1 | 10 | 1 |
| **Mod** | +0 | +1 | +1 | -5 | +0 | -5 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** —
**Damage Vulnerabilities:** fire
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**False Objects.** If the swarm is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the swarm move or act, that creature must succeed on a DC 15 Wisdom (Perception) check to discern that the swarm is animate.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a 1-foot-tall, 8-inch-wide, 2-inch-thick object. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Book Club.** Melee Weapon Attack: +3 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 6 (2d4 + 1) bludgeoning damage, or 3 (1d4 + 1) bludgeoning damage if the swarm has half its hit points or fewer.


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