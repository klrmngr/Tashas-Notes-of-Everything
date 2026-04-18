---
type: pc
race: "Fey"
class:
 - "Pixie"
subClass:
 - "CR 1/4"
cover: "Pixie.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1-4
  - source/mm
---
###### Pixie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Pixie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 1 (1d4 - 1) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 20 | 8 | 10 | 14 | 15 |
| **Mod** | -4 | +5 | -1 | +0 | +2 | +2 |

**Speed:** 10 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Sylvan
**Skills:** Perception +4, Stealth +7

---

### Traits

**Magic Resistance.** The pixie has advantage on saving throws against spells and other magical effects.


---

### Actions

**Superior Invisibility.** The pixie magically turns invisible until its concentration ends (as if concentrating on a spell). Any equipment the pixie wears or carries is invisible with it.


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