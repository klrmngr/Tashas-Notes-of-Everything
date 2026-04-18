---
type: pc
race: "Fey"
class:
 - "Giant Ox"
subClass:
 - "CR 3"
cover: "Giant Ox.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/huge
  - cr/3
  - source/bgg
---
###### Giant Ox
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Giant Ox.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Huge Fey |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 105 (10d12 + 40) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 19 | 4 | 11 | 9 |
| **Mod** | +6 | +0 | +4 | -3 | +0 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands Giant and Sylvan but can't speak

---

### Traits

**Beast of Burden.** The ox is considered to be one size larger for the purpose of determining its carrying capacity.


---

### Actions

**Gore.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 13 (2d6 + 6) piercing damage. If the ox moved at least 20 feet straight toward the target immediately before the hit, the target takes an extra 7 (2d6) piercing damage, and it must succeed on a DC 16 Strength saving throw or have the prone condition.


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