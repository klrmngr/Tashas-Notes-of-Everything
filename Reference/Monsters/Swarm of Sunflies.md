---
type: pc
race: "Swarm of Tiny Celestials"
class:
 - "Swarm of Sunflies"
subClass:
 - "CR 1"
cover: "Swarm of Sunflies.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/1
  - source/mpp
---
###### Swarm of Sunflies
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Swarm of Sunflies.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Celestials |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Swarm of Tiny Celestials |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 17 | 10 | 4 | 10 | 6 |
| **Mod** | -2 | +3 | +0 | -3 | +0 | -2 |

**Speed:** 10 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands Celestial but can't speak

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny dragonfly. The swarm can't regain hit points or gain temporary hit points.


---

### Actions

**Stings.** Melee Weapon Attack: +5 to hit, reach 0 ft., one creature in the swarm's space. *Hit:* 10 (3d4 + 3) piercing damage, or 5 (1d4 + 3) piercing damage if the swarm has half of its hit points or fewer. Additionally, if the swarm is on an Outer Plane, it injects the target with a toxin, the effect of which is determined by the swarm's location:

**Upper Plane.** The target sheds bright light in a 5-foot radius until the end of its next turn. During that time, the invisible condition has no effect on it.

**Neutral Plane.** If the target is concentrating on a spell or similar effect, it loses its concentration.

**Lower Plane.** The target's speed is reduced by 10 feet until the end of its next turn.

**Dazzling Lights (Recharge 6).** The swarm shines its lights in a dazzling display. Each creature within 15 feet of the swarm must succeed on a DC 10 Constitution saving throw or have the stunned condition for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Illumination.** The swarm sheds bright light in a 15-foot radius and dim light for an additional 15 feet, or it uses a bonus action to extinguish the light.


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