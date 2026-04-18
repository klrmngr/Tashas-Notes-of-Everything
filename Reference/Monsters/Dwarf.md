---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Dwarf"
subClass:
 - "CR 1/4"
cover: "Dwarf.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/awm
---
###### Dwarf
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Dwarf.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 30 |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 14 | 10 | 11 | 10 |
| **Mod** | +3 | +1 | +2 | +0 | +0 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —
**Damage Resistances:** poison

---

### Traits

**Dwarven Resilience.** They have advantage on saving throws against poison, and they have resistance to poison damage.


---

### Actions

**Shortbow.** Melee Weapon Attack: +3 to hit, one target. *Hit:* 4 (1d6 + 1) slashing damage.


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