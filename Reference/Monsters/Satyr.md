---
type: pc
race: "Fey"
class:
 - "Satyr"
subClass:
 - "CR 1/2"
cover: "Satyr.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/1-2
  - source/mm
---
###### Satyr
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Satyr.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 11 | 12 | 10 | 14 |
| **Mod** | +1 | +3 | +0 | +1 | +0 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Elvish, Sylvan
**Skills:** Perception +2, Performance +6, Stealth +5

---

### Traits

**Magic Resistance.** The satyr has advantage on saving throws against spells and other magical effects.


---

### Actions

**Ram.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 6 (2d4 + 1) bludgeoning damage.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Shortbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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