---
type: pc
race: "Swarm of Tiny Monstrositys"
class:
 - "Swarm of Hoard Scarabs"
subClass:
 - "CR 2"
cover: "Swarm of Hoard Scarabs.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/ftd
---
###### Swarm of Hoard Scarabs
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Swarm of Hoard Scarabs.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Monstrositys |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Swarm of Tiny Monstrositys |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 16 | 11 | 3 | 8 | 6 |
| **Mod** | -2 | +3 | +0 | -4 | -1 | -2 |

**Speed:** 20 ft., burrow 20 ft., fly 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 60 ft., passive Perception 9
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**False Appearance.** If the swarm is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the swarm move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the swarm is animate.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny scarab. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Swarm of Bites.** Melee Weapon Attack: +5 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 13 (3d6 + 3) piercing damage, or 6 (1d6 + 3) piercing damage if the swarm is at half of its hit points or fewer, and the target has disadvantage on attack rolls until the start of its next turn.


---

### Bonus Actions

**Scale Dust (1/Day).** The swarm releases magical glittering dust from its wings. Each creature within 10 feet of the swarm must succeed on a DC 13 Dexterity saving throw or be outlined in blue light for 10 minutes. While outlined in this way, a creature sheds dim light in a 10-foot radius and can't benefit from being invisible. In addition, every Dragon within 1 mile of the creature becomes aware of it and can unerringly track the creature. Casting dispel magic on the creature ends the effect on it.


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