---
type: pc
race: "Beast"
class:
 - "Giant Fire Beetle"
subClass:
 - "CR 0"
cover: "Giant Fire Beetle.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/0
  - source/mm
---
###### Giant Fire Beetle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Giant Fire Beetle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 4 (1d6 + 1) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 10 | 12 | 1 | 7 | 3 |
| **Mod** | -1 | +0 | +1 | -5 | -2 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 8
**Languages:** —

---

### Traits

**Illumination.** The beetle sheds bright light in a 10-foot radius and dim light for an additional 10 ft..


---

### Actions

**Bite.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) slashing damage.


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