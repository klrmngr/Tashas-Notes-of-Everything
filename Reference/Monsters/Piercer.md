---
type: pc
race: "Monstrosity"
class:
 - "Piercer"
subClass:
 - "CR 1/2"
cover: "Piercer.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1-2
  - source/mm
---
###### Piercer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Piercer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 22 (3d8 + 9) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 16 | 1 | 7 | 3 |
| **Mod** | +0 | +1 | +3 | -5 | -2 | -4 |

**Speed:** 5 ft., climb 5 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 60 ft., passive Perception 8
**Languages:** —
**Skills:** Stealth +5

---

### Traits

**False Appearance.** While the piercer remains motionless on the ceiling, it is indistinguishable from a normal stalactite.

**Spider Climb.** The piercer can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Drop.** Melee Weapon Attack: +3 to hit, one creature directly underneath the piercer. *Hit:* 3 (1d6) piercing damage per 10 feet fallen, up to 21 (6d6). Miss: The piercer takes half the normal falling damage for the distance fallen.


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