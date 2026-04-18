---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Lords' Alliance Guard"
subClass:
 - "CR 1/4"
cover: "Lords' Alliance Guard.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/oota
---
###### Lords' Alliance Guard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Lords' Alliance Guard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 (chain shirt, shield) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 12 | 10 | 11 | 10 |
| **Mod** | +2 | +1 | +1 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** —
**Skills:** Perception +2

---

### Traits

**Dwarven Resilience.** The guard has advantage on saving throws against poison.


---

### Actions

**Halberd.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 7 (1d10 + 2) slashing damage.


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