---
type: pc
race: "Humanoid (quaggoth)"
class:
 - "Quaggoth Thonot"
subClass:
 - "CR 3"
cover: "Quaggoth Thonot.png"
campaign:
locations:
tags:
  - race/quaggoth
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/mm
---
###### Quaggoth Thonot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Quaggoth Thonot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (quaggoth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Humanoid (quaggoth) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 16 | 6 | 12 | 7 |
| **Mod** | +3 | +1 | +3 | -2 | +1 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Undercommon
**Skills:** Athletics +5
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Wounded Fury.** While it has 10 hit points or fewer, the quaggoth has advantage on attack rolls. In addition, it deals an extra 7 (2d6) damage to any target it hits with a melee attack.


---

### Actions

**Multiattack.** The quaggoth makes two claw attacks.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


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