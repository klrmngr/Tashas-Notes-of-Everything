---
type: pc
race: "Fiend"
class:
 - "Larva"
subClass:
 - "CR 0"
cover: "Larva.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/0
  - source/dmg
---
###### Larva
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dungeon Master's Guide
___

> [!infobox|no-t right]
> ![[Larva.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Dungeon Master's Guide |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 9 | 10 | 6 | 10 | 2 |
| **Mod** | -1 | -1 | +0 | -2 | +0 | -4 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands the languages it knew in life but can't speak

---

### Actions

**Bite.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 1 (1d4 - 1) piercing damage.


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