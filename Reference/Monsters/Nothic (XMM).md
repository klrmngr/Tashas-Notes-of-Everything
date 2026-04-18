---
type: pc
race: "Aberration"
class:
 - "Nothic"
subClass:
 - "CR 2"
cover: "Nothic.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/2
  - source/xmm
---
###### Nothic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Nothic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 16 | 13 | 10 | 8 |
| **Mod** | +2 | +3 | +3 | +1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 14
**Languages:** Undercommon
**Skills:** Arcana +3, Insight +4, Perception +4, Stealth +5

---

### Actions

**Multiattack.** The nothic makes two Claw attacks.

**Claw.** m +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Slashing damage.

**Rotting Gaze.** con DC 13, one creature the nothic can see within 120 feet.  17 (5d6) Necrotic damage.  Half damage.


---

### Bonus Actions

**Weird Insight (Recharge 6).** wis DC 14, one creature the nothic can see within 120 feet.  The nothic magically learns one fact or secret about the target.


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