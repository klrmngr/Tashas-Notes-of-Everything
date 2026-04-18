---
type: pc
race: "Humanoid (wizard)"
class:
 - "Quandrix Apprentice"
subClass:
 - "CR 2"
cover: "Quandrix Apprentice.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/scc
---
###### Quandrix Apprentice
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Quandrix Apprentice.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 13 | 15 | 14 | 11 |
| **Mod** | +0 | +1 | +1 | +2 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus any two languages
**Saving Throws:** Int +4, Wis +4
**Skills:** Arcana +6, Investigation +6, Nature +4

---

### Actions

**Multiattack.** The apprentice makes two Exponential Lash attacks.

**Exponential Lash.** Melee or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 5 (1d6 + 2) force damage, and the apprentice can cause one creature it can see within 30 feet of the target to take 9 (2d6 + 2) force damage.


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