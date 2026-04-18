---
type: pc
race: "Construct"
class:
 - "Monodrone"
subClass:
 - "CR 1/8"
cover: "Monodrone.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-8
  - source/mm
---
###### Monodrone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Monodrone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 5 (1d8 + 1) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 12 | 4 | 10 | 5 |
| **Mod** | +0 | +1 | +1 | -3 | +0 | -3 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 10
**Languages:** Modron

---

### Traits

**Axiomatic Mind.** The monodrone can't be compelled to act in a manner contrary to its nature or its instructions.

**Disintegration.** If the monodrone dies, its body disintegrates into dust, leaving behind its weapons and anything else it was carrying.


---

### Actions

**Dagger.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.

**Javelin.** Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 3 (1d6) piercing damage.


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