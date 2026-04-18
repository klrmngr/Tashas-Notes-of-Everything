---
type: pc
race: "Swarm of Tiny Monstrositys"
class:
 - "Swarm of Gremishkas"
subClass:
 - "CR 2"
cover: "Swarm of Gremishkas.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/vrgr
---
###### Swarm of Gremishkas
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Swarm of Gremishkas.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Monstrositys |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 24 (7d6) |
> | :FasUserGroup: Race | Swarm of Tiny Monstrositys |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 10 | 12 | 14 | 4 |
| **Mod** | +1 | +2 | +0 | +1 | +2 | -3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 14
**Languages:** understands Common but can't speak
**Skills:** Perception +4
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Limited Spell Immunity.** The swarm automatically succeeds on saving throws against spells of 3rd level or lower, and the attack rolls of such spells always miss it.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny gremishka. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Bites.** Melee Weapon Attack: +4 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 12 (3d6 + 2) piercing damage, or 5 (1d6 + 2) piercing damage if the swarm has half of its hit points or fewer, plus 7 (2d6) force damage.


---

### Reactions

**Spell Redirection.** In response to a spell attack roll missing the swarm, the swarm causes that spell to hit another creature of its choice within 30 feet of it that it can see.


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