---
type: pc
race: "Aberration"
class:
 - "Kuo-toa Monitor"
subClass:
 - "CR 3"
cover: "Kuo-toa Monitor.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/3
  - source/xmm
---
###### Kuo-toa Monitor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Kuo-toa Monitor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 14 | 12 | 14 | 11 |
| **Mod** | +3 | +0 | +2 | +1 | +2 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., Truesight 30 ft., passive Perception 16
**Languages:** Undercommon
**Skills:** Perception +6, Religion +3

---

### Traits

**Amphibious.** The kuo-toa can breathe air and water.

**Sunlight Sensitivity.** While in sunlight, the kuo-toa has Disadvantage on ability checks and attack rolls.


---

### Actions

**Multiattack.** The kuo-toa makes two Bone Whip attacks.

**Bone Whip.** m +5, reach 10 ft. *Hit:* 6 (1d6 + 3) Slashing damage plus 7 (2d6) Lightning damage, and the target can't make Opportunity Attacks until the start of the kuo-toa's next turn.


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