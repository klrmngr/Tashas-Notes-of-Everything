---
type: pc
race: "Swarm of Tiny Beasts"
class:
 - "Swarm of Quippers"
subClass:
 - "CR 1"
cover: "Swarm of Quippers.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1
  - source/mm
---
###### Swarm of Quippers
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Swarm of Quippers.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Beasts |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 28 (8d8 - 8) |
> | :FasUserGroup: Race | Swarm of Tiny Beasts |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 9 | 1 | 7 | 2 |
| **Mod** | +1 | +3 | -1 | -5 | -2 | -4 |

**Speed:** 0 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Blood Frenzy.** The swarm has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny quipper. The swarm can't regain hit points or gain temporary hit points.

**Water Breathing.** The swarm can breathe only underwater.


---

### Actions

**Bites.** Melee Weapon Attack: +5 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 14 (4d6) piercing damage, or 7 (2d6) piercing damage if the swarm has half of its hit points or fewer.


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