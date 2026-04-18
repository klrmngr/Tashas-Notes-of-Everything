---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Istrid Horn"
subClass:
 - "CR 8"
cover: "Istrid Horn.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/wdh
---
###### Istrid Horn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Istrid Horn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 117 (18d8 + 36) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 14 | 11 | 17 | 13 |
| **Mod** | +1 | +0 | +2 | +0 | +3 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Dwarvish
**Saving Throws:** Con +5, Wis +6
**Skills:** Intimidation +4, Religion +3
**Damage Resistances:** poison

---

### Traits

**Dwarven Resilience.** Istrid has advantage on saving throws against being poisoned.


---

### Actions

**Multiattack.** Istrid makes two melee attacks.

**Maul.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 8 (2d6 + 1) bludgeoning damage.

**Treasure Sense (3/Day).** Istrid magically pinpoints precious metals and stones, such as coins and gems, within 60 feet of her.


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