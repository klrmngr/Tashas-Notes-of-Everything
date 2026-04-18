---
type: pc
race: "Aberration"
class:
 - "Kuo-toa Archpriest"
subClass:
 - "CR 6"
cover: "Kuo-toa Archpriest.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/xmm
---
###### Kuo-toa Archpriest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Kuo-toa Archpriest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 105 (14d8 + 42) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 13 | 16 | 14 |
| **Mod** | +3 | +2 | +3 | +1 | +3 | +2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., Truesight 30 ft., passive Perception 19
**Languages:** Undercommon
**Skills:** Perception +9, Religion +4

---

### Traits

**Amphibious.** The kuo-toa can breathe air and water.

**Sunlight Sensitivity.** While in sunlight, the kuo-toa has Disadvantage on ability checks and attack rolls.


---

### Actions

**Multiattack.** The kuo-toa makes three Strange Scepter attacks.

**Strange Scepter.** m,r +6, reach 5 ft. or range 120 ft. *Hit:* 20 (5d6 + 3) Lightning damage.


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