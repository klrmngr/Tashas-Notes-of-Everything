---
type: pc
race: "Swarm of Tiny Beasts"
class:
 - "Swarm of Maggots"
subClass:
 - "CR 2"
cover: "Swarm of Maggots.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/2
  - source/vrgr
---
###### Swarm of Maggots
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Swarm of Maggots.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Beasts |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Swarm of Tiny Beasts |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 12 | 10 | 1 | 7 | 1 |
| **Mod** | -4 | +1 | +0 | -5 | -2 | -5 |

**Speed:** 20 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., passive Perception 8
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny maggot. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Infestation.** Melee Weapon Attack: +3 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 10 (4d4) piercing damage, or 5 (2d4) piercing damage if the swarm has half of its hit points or fewer. A creature damaged by the swarm must succeed on a DC 12 Constitution saving throw or contract a disease.
Each time the diseased creature finishes a long rest, roll a d6 to determine the disease's effect:
- **1-2.** The creature is blinded until it finishes a long rest.
- **3-4.** The creature's hit point maximum decreases by 5 (2d4), and the reduction can't be removed until the disease ends. The creature dies if its hit point maximum drops to 0.
- **5-6.** The creature has disadvantage on ability checks and attack rolls until it finishes its next long rest.
  The disease lasts until it's removed by magic or until the creature rolls the same random effect for the disease two long rests in a row.


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