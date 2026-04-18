---
type: pc
race: "Aberration"
class:
 - "Kuo-toa Marauder"
subClass:
 - "CR 1/2"
cover: "Kuo-toa Marauder.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/1-2
  - source/hotb
---
###### Kuo-toa Marauder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Kuo-toa Marauder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 12 | 10 | 11 | 10 |
| **Mod** | +2 | +0 | +1 | +0 | +0 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., Truesight 30 ft., passive Perception 14
**Languages:** Common, Undercommon
**Skills:** Perception +4

---

### Traits

**Amphibious.** The kuo-toa can breathe air and water.

**Sunlight Sensitivity.** While in sunlight, the kuo-toa has Disadvantage on ability checks and attack rolls.


---

### Actions

**Brine Slicer.** m +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Slashing damage.


---

### Bonus Actions

**Slippery.** The kuo-toa takes the Disengage action.


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