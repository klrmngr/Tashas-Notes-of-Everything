---
type: pc
race: "Aberration"
class:
 - "Neogi Hatchling"
subClass:
 - "CR 1/8"
cover: "Neogi Hatchling.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/1-8
  - source/mpmm
---
###### Neogi Hatchling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Neogi Hatchling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Aberration |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 7 (3d4) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 13 | 10 | 6 | 10 | 9 |
| **Mod** | -4 | +1 | +0 | -2 | +0 | -1 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —

---

### Traits

**Mental Fortitude.** The neogi has advantage on saving throws against being charmed or frightened, and magic can't put the neogi to sleep.

**Spider Climb.** The neogi can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage plus 3 (1d6) poison damage, and the target must succeed on a DC 10 Constitution saving throw or become poisoned for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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