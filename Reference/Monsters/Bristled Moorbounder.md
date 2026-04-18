---
type: pc
race: "Beast"
class:
 - "Bristled Moorbounder"
subClass:
 - "CR 3"
cover: "Bristled Moorbounder.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/3
  - source/egw
---
###### Bristled Moorbounder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Bristled Moorbounder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 14 | 2 | 13 | 5 |
| **Mod** | +4 | +2 | +2 | -4 | +1 | -3 |

**Speed:** 70 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** —

---

### Traits

**Bladed Hide.** At the start of each of its turns, the moorbounder deals 5 (2d4) piercing damage to any creature grappling it.

**Standing Leap.** The moorbounder's long jump is up to 40 feet and its high jump is up to 20 feet, with or without a running start.


---

### Actions

**Multiattack.** The moorbounder makes two attacks: one with its blades and one with its claws.

**Blades.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 14 (4d4 + 4) slashing damage.


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