---
type: pc
race: "Humanoid"
class:
 - "Guard Captain"
subClass:
 - "CR 4"
cover: "Guard Captain.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/xmm
---
###### Guard Captain
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Guard Captain.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 16 | 12 | 14 | 13 |
| **Mod** | +4 | +2 | +3 | +1 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common
**Skills:** Athletics +6, Perception +4

---

### Actions

**Multiattack.** The guard makes two attacks, using Javelin or Longsword in any combination.

**Javelin.** m,r +6, reach 5 ft. or range 30/120 ft. *Hit:* 14 (3d6 + 4) Piercing damage.

**Longsword.** m +6, reach 5 ft. *Hit:* 15 (2d10 + 4) Slashing damage.


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