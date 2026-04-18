---
type: pc
race: "Swarm of Small Fiends"
class:
 - "Swarm of Gibberlings"
subClass:
 - "CR 3"
cover: "Swarm of Gibberlings.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/3
  - source/qftis
---
###### Swarm of Gibberlings
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Swarm of Gibberlings.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Swarm of Small Fiends |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 38 (7d10) |
> | :FasUserGroup: Race | Swarm of Small Fiends |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 11 | 5 | 7 | 5 |
| **Mod** | +4 | +2 | +0 | -3 | -2 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 8
**Languages:** Gibberling
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Aversion to Fire.** If the swarm takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.

**Incessant Gibberish.** Any non-gibberling that is within 60 feet of the swarm and doesn't have the deafened condition has disadvantage on Constitution saving throws to maintain concentration on spells and similar effects.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough to accommodate a Small gibberling. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Multiattack.** The swarm makes two Gnashing Teeth attacks.

**Gnashing Teeth.** Melee Weapon Attack: +6 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 14 (4d4 + 4) piercing damage, or 9 (2d4 + 4) piercing damage if the swarm has half of its hit points or fewer.


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