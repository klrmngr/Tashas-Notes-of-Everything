---
type: pc
race: "Aberration"
class:
 - "Kuo-toa Whip"
subClass:
 - "CR 1"
cover: "Kuo-toa Whip.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/1
  - source/xmm
---
###### Kuo-toa Whip
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Kuo-toa Whip.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 12 | 14 | 11 |
| **Mod** | +2 | +0 | +2 | +1 | +2 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., Truesight 30 ft., passive Perception 16
**Languages:** Undercommon
**Skills:** Perception +6, Religion +3

---

### Traits

**Amphibious.** The kuo-toa can breathe air and water.

**Sunlight Sensitivity.** While in sunlight, the kuo-toa has Disadvantage on ability checks and attack rolls.


---

### Actions

**Pincer Staff.** m +4, reach 10 ft. *Hit:* 9 (2d6 + 2) Piercing damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 12). Until the grapple ends, the kuo-toa can't make Pincer Staff attacks.

**Conjure Slimy Glob.** r +4, range 60 ft. *Hit:* 9 (3d4 + 2) Acid damage.


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