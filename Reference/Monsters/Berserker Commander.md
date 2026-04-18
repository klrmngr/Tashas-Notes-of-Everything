---
type: pc
race: "Humanoid"
class:
 - "Berserker Commander"
subClass:
 - "CR 8"
cover: "Berserker Commander.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/xmm
---
###### Berserker Commander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Berserker Commander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 19 | 10 | 14 | 9 |
| **Mod** | +4 | +2 | +4 | +0 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common
**Saving Throws:** Str +7, Con +7
**Skills:** Athletics +7, Perception +5
**Condition Immunities:** charmed; frightened

---

### Traits

**Bloodied Frenzy.** While Bloodied, the berserker has Advantage on attack rolls and saving throws.


---

### Actions

**Multiattack.** The berserker makes three attacks, using Greataxe or Javelin in any combination.

**Greataxe.** m +7, reach 5 ft. *Hit:* 10 (1d12 + 4) Slashing damage, plus 10 (3d6) Thunder damage to the target or another creature within 5 feet of the target.

**Javelin.** m,r +7, reach 5 ft. or range 30/120 ft. *Hit:* 18 (4d6 + 4) Piercing damage, and the target's Speed decreases by 5 feet until the start of the berserker's next turn.


---

### Bonus Actions

**Frenzied Rush.** Each ally within 30 feet of the berserker can take a Reaction to move up to half the ally's Speed without provoking Opportunity Attacks. The berserker can also move up to half its Speed without provoking Opportunity Attacks.


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