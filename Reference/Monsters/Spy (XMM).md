---
type: pc
race: "Humanoid"
class:
 - "Spy"
subClass:
 - "CR 1"
cover: "Spy.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/xmm
---
###### Spy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Spy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 10 | 12 | 14 | 16 |
| **Mod** | +0 | +2 | +0 | +1 | +2 | +3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus one other language
**Skills:** Deception +5, Insight +4, Investigation +5, Perception +6, Sleight Of Hand +4, Stealth +6

---

### Actions

**Shortsword.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 7 (2d6) Poison damage.

**Hand Crossbow.** r +4, range 30/120 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 7 (2d6) Poison damage.


---

### Bonus Actions

**Cunning Action.** The spy takes the Dash, Disengage, or Hide action.


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