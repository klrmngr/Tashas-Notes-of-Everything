---
type: pc
race: "Beast"
class:
 - "Giant Shark"
subClass:
 - "CR 5"
cover: "Giant Shark.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/5
  - source/mm
---
###### Giant Shark
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Giant Shark.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 126 (11d12 + 55) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 11 | 21 | 1 | 10 | 5 |
| **Mod** | +6 | +0 | +5 | -5 | +0 | -3 |

**Speed:** swim 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Traits

**Blood Frenzy.** The shark has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Water Breathing.** The shark can breathe only underwater.


---

### Actions

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 22 (3d10 + 6) piercing damage.


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