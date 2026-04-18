---
type: pc
race: "Construct"
class:
 - "Animated Coffin"
subClass:
 - "CR 3"
cover: "Animated Coffin.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/3
  - source/aatm
---
###### Animated Coffin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AATM
___

> [!infobox|no-t right]
> ![[Animated Coffin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 60 (8d10 + 16) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | AATM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 15 | 3 | 11 | 3 |
| **Mod** | +3 | +1 | +2 | -4 | +0 | -4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (can't see beyond this radius), passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** If the animated coffin is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the coffin move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the coffin is animate.

**Spider Climb.** The animated coffin can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The animated coffin makes two Slam attacks.

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) bludgeoning damage.

**Entrap.** Melee Weapon Attack: +5 to hit, reach 5 ft., one Large or smaller creature. *Hit:* The target has the grappled condition (escape DC 13). Until this grapple ends, if the target is not an Undead, the target has the restrained condition and takes 14 (4d6) piercing damage at the start of each of its turns. The animated coffin can grapple only one creature at a time.


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