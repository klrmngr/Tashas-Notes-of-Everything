---
type: pc
race: "Humanoid"
class:
 - "Squire"
subClass:
 - "CR —"
cover: "Squire.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/hol
---
###### Squire
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HoL
___

> [!infobox|no-t right]
> ![[Squire.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 (shield) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | HoL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 10 | 12 | 8 | 11 | 9 |
| **Mod** | +1 | +0 | +1 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** any one language (usually Common)
**Saving Throws:** Str +3
**Skills:** Athletics +3

---

### Actions

**Longsword.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage if used with two hands.


---

### Bonus Actions

**Shove.** While wielding a shield, you try to shove one creature within 5 feet of you.


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