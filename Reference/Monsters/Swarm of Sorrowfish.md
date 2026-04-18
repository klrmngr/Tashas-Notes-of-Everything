---
type: pc
race: "Swarm of Tiny Aberrations"
class:
 - "Swarm of Sorrowfish"
subClass:
 - "CR 6"
cover: "Swarm of Sorrowfish.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/crcotn
---
###### Swarm of Sorrowfish
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Swarm of Sorrowfish.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Aberrations |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 104 (16d8 + 32) |
> | :FasUserGroup: Race | Swarm of Tiny Aberrations |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 19 | 14 | 1 | 11 | 3 |
| **Mod** | +3 | +4 | +2 | -5 | +0 | -4 |

**Speed:** 0 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through an opening as narrow as 1 foot wide. The swarm can't regain hit points or gain temporary hit points.

**Virulent Sorrow.** Each time the swarm takes damage, any creature within 5 feet of it must make a DC 13 Wisdom saving throw. On a failed saving throw, the creature suffers the following effects until the end of its next turn: it has disadvantage on its attack rolls, it can't take reactions, and its speed is halved.

**Water Breathing.** The swarm can breathe only underwater.


---

### Actions

**Swarm of Bites.** Melee Weapon Attack: +8 to hit, reach 0 ft., one target in the swarm's space. *Hit:* 21 (6d6) piercing damage, or 10 (3d6) piercing damage if the swarm has half its hit points or fewer.

**Desolate Drain (Recharge 5–6).** Each creature in the swarm's space must make a DC 13 Wisdom saving throw. On a failed saving throw, a creature takes 24 (7d6) psychic damage and is stunned until the end of its next turn. The effect ends on a creature if the swarm moves out of the creature's space or if another creature within 5 feet of the swarm uses an action to make a DC 14 Strength check, pulling the affected creature out of the swarm on a successful check. On a successful saving throw, a creature takes half as much damage and suffers no other effects.


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