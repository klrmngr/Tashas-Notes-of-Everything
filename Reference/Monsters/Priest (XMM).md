---
type: pc
race: "Humanoid (cleric)"
class:
 - "Priest"
subClass:
 - "CR 2"
cover: "Priest.png"
campaign:
locations:
tags:
  - race/cleric
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/xmm
---
###### Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (cleric) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Humanoid (cleric) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 12 | 13 | 16 | 13 |
| **Mod** | +3 | +0 | +1 | +1 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus one other language
**Skills:** Medicine +7, Perception +5, Religion +5

---

### Actions

**Multiattack.** The priest makes two attacks, using Mace or Radiant Flame in any combination.

**Mace.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Bludgeoning damage plus 5 (2d4) Radiant damage.

**Radiant Flame.** r +5, range 60 ft. *Hit:* 11 (2d10) Radiant damage.


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