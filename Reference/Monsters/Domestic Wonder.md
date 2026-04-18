---
type: pc
race: "Construct"
class:
 - "Domestic Wonder"
subClass:
 - "CR 0"
cover: "Domestic Wonder.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/0
  - source/fraif
---
###### Domestic Wonder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Domestic Wonder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 5 (1d8 + 1) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 8 | 13 | 3 | 8 | 1 |
| **Mod** | +1 | -1 | +1 | -4 | -1 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** —

---

### Traits

**Mechanical Determination.** If damage reduces the wonder to 0 Hit Points, it makes a Constitution saving throw with a DC of 5 plus the damage taken unless the damage is Lightning or from a Critical Hit. On a successful save, the wonder drops to 1 Hit Point instead.

**Wind-Up Operation.** The wonder has the Unconscious condition until another creature winds it with the wonder's unique key for 1 minute. Once wound, the wonder operates for 10 days or until a creature touches the wonder with its key as a Utilize action to deactivate it, after which the wonder has the Unconscious condition until it is wound again.


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