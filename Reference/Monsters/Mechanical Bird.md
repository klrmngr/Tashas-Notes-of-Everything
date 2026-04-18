---
type: pc
race: "Construct"
class:
 - "Mechanical Bird"
subClass:
 - "CR Unknown"
cover: "Mechanical Bird.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/Unknown
  - source/wdh
---
###### Mechanical Bird
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Mechanical Bird.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | Unknown (— XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 1 |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +0 | +0 |

**Speed:** fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Actions

**Slam.** Melee Weapon Attack: +0 to hit, reach 5 ft., one target. *Hit:* 2 (1d3) piercing damage, and the bird is destroyed by the impact.


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