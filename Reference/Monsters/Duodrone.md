---
type: pc
race: "Construct"
class:
 - "Duodrone"
subClass:
 - "CR 1/4"
cover: "Duodrone.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-4
  - source/mm
---
###### Duodrone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Duodrone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 13 | 12 | 6 | 10 | 7 |
| **Mod** | +0 | +1 | +1 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 10
**Languages:** Modron

---

### Traits

**Axiomatic Mind.** The duodrone can't be compelled to act in a manner contrary to its nature or its instructions.

**Disintegration.** If the duodrone dies, its body disintegrates into dust, leaving behind its weapons and anything else it was carrying.


---

### Actions

**Multiattack.** The duodrone makes two fist attacks or two javelin attacks.

**Fist.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.

**Javelin.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage.


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