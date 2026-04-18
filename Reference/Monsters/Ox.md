---
type: pc
race: "Beast (cattle)"
class:
 - "Ox"
subClass:
 - "CR 1/4"
cover: "Ox.png"
campaign:
locations:
tags:
  - race/cattle
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1-4
  - source/mpmm
---
###### Ox
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Ox.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Large Beast (cattle) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 15 (2d10 + 4) |
> | :FasUserGroup: Race | Beast (cattle) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 14 | 2 | 10 | 4 |
| **Mod** | +4 | +0 | +2 | -4 | +0 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —

---

### Traits

**Beast of Burden.** The ox is considered to be one size larger for the purpose of determining its carrying capacity.


---

### Actions

**Gore.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage. If the ox moved at least 20 feet straight toward the target immediately before the hit, the target takes an extra 7 (2d6) piercing damage.


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