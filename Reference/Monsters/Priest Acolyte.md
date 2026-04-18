---
type: pc
race: "Humanoid (cleric)"
class:
 - "Priest Acolyte"
subClass:
 - "CR 1/4"
cover: "Priest Acolyte.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/xmm
---
###### Priest Acolyte
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Priest Acolyte.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (cleric) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (cleric) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 12 | 10 | 14 | 11 |
| **Mod** | +2 | +0 | +1 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Skills:** Medicine +4, Religion +2

---

### Actions

**Mace.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Bludgeoning damage plus 2 (1d4) Radiant damage.

**Radiant Flame.** r +4, range 60 ft. *Hit:* 7 (2d6) Radiant damage.


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