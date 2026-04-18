---
type: pc
race: "Celestial"
class:
 - "Sunfly"
subClass:
 - "CR 0"
cover: "Sunfly.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/tiny
  - cr/0
  - source/mpp
---
###### Sunfly
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Sunfly.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Celestial |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 2 (1d4) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 17 | 10 | 4 | 10 | 6 |
| **Mod** | -3 | +3 | +0 | -3 | +0 | -2 |

**Speed:** 10 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands Celestial but can't speak

---

### Actions

**Sting.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) piercing damage. Additionally, if the sunfly is on an Outer Plane, it injects the target with a toxin, the effect of which is determined by the sunfly's location:

**Upper Plane.** The target sheds bright light in a 5-foot radius until the end of its next turn.

**Neutral Plane.** If the target is concentrating on a spell or similar effect, it makes the Constitution saving throw with disadvantage to maintain its concentration.

**Lower Plane.** The target's speed is reduced by 5 feet until the end of its next turn.


---

### Bonus Actions

**Illumination.** The sunfly sheds bright light in a 5-foot radius and dim light for an additional 5 feet, or it uses a bonus action to extinguish the light.


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