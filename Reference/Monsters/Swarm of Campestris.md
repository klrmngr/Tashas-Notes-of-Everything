---
type: pc
race: "Swarm of Tiny Plants"
class:
 - "Swarm of Campestris"
subClass:
 - "CR 1"
cover: "Swarm of Campestris.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1
  - source/wbtw
---
###### Swarm of Campestris
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Swarm of Campestris.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Plants |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Swarm of Tiny Plants |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 7 | 10 | 4 | 10 | 8 |
| **Mod** | -4 | -2 | +0 | -3 | +0 | -1 |

**Speed:** 5 ft. &nbsp;|&nbsp; **Senses:** tremorsense 30 ft., passive Perception 14
**Languages:** understands Common but speaks only through the use of its Mimicry trait
**Skills:** Perception +4
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Mimicry.** Each campestri in the swarm can mimic any voice or song it has heard, albeit in a nasal falsetto.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough to accommodate an individual campestri. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Head Butts.** Melee Weapon Attack: +0 to hit, reach 5 ft., one target. *Hit:* 10 (4d4) bludgeoning damage, or 5 (2d4) bludgeoning damage if the swarm has half its hit points or fewer.

**Spores (1/Day).** A 20-foot radius of spores extends from the swarm. These spores can go around corners, and they have no effect on Constructs, Elementals, Plants, or Undead. Each other creature in the area must make a DC 10 Wisdom saving throw. On a failed save, the creature is incapacitated and its speed is halved, both for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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