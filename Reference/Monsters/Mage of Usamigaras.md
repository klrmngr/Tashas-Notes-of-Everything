---
type: pc
race: "Humanoid"
class:
 - "Mage of Usamigaras"
subClass:
 - "CR 1/8"
cover: "Mage of Usamigaras.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/qftis
---
###### Mage of Usamigaras
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Mage of Usamigaras.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 10 | 15 | 10 | 13 |
| **Mod** | +0 | +1 | +0 | +2 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Skills:** Arcana +4, Deception +5, Sleight Of Hand +3

---

### Actions

**Arcane Burst.** Melee or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 7 (1d10 + 2) force damage.


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