---
type: pc
race: "Beast"
class:
 - "Spotted Lion"
subClass:
 - "CR 3"
cover: "Spotted Lion.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/3
  - source/bgg
---
###### Spotted Lion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Spotted Lion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 66 (7d12 + 21) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 14 | 17 | 5 | 13 | 10 |
| **Mod** | +6 | +2 | +3 | -3 | +1 | +0 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5, Stealth +6

---

### Traits

**Pack Tactics.** The lion has advantage on an attack roll against a creature if at least one of the lion's allies is within 5 feet of the target and the ally doesn't have the incapacitated condition.


---

### Actions

**Rend.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) piercing damage. If the lion moved at least 20 feet straight toward the target immediately before the hit, the target must succeed on a DC 16 Strength saving throw or have the prone condition. If the target has the prone condition, the lion can make another Rend attack against it as a bonus action.


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