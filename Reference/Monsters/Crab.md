---
type: pc
race: "Beast"
class:
 - "Crab"
subClass:
 - "CR 0"
cover: "Crab.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/tiny
  - cr/0
  - source/mm
---
###### Crab
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Crab.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Beast |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 2 (1d4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 11 | 10 | 1 | 8 | 2 |
| **Mod** | -4 | +0 | +0 | -5 | -1 | -4 |

**Speed:** 20 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 9
**Languages:** —
**Skills:** Stealth +2

---

### Traits

**Amphibious.** The crab can breathe air and water.


---

### Actions

**Claw.** Melee Weapon Attack: +0 to hit, reach 5 ft., one target. *Hit:* 1 bludgeoning damage.


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