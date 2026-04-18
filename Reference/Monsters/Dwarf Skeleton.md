---
type: pc
race: "Undead"
class:
 - "Dwarf Skeleton"
subClass:
 - "CR 1/2"
cover: "Dwarf Skeleton.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1-2
  - source/pabtso
---
###### Dwarf Skeleton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Dwarf Skeleton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (chain shirt) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 15 | 6 | 8 | 5 |
| **Mod** | +3 | +0 | +2 | -2 | -1 | -3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** understands Dwarvish but can't speak
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Sure-Footed.** The skeleton has advantage on Strength and Dexterity saving throws made against effects that make it have the prone condition.


---

### Actions

**Battleaxe.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.


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