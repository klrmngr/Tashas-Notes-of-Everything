---
type: pc
race: "Plant"
class:
 - "Awakened Shrub"
subClass:
 - "CR 0"
cover: "Awakened Shrub.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/0
  - source/mm
---
###### Awakened Shrub
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Awakened Shrub.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 10 (3d6) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 8 | 11 | 10 | 10 | 6 |
| **Mod** | -4 | -1 | +0 | +0 | +0 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** one language known by its creator
**Damage Vulnerabilities:** fire
**Damage Resistances:** piercing

---

### Traits

**False Appearance.** While the shrub remains motionless, it is indistinguishable from a normal shrub.


---

### Actions

**Rake.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 1 (1d4 - 1) slashing damage.


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