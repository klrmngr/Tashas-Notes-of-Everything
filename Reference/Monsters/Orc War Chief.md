---
type: pc
race: "Humanoid (orc)"
class:
 - "Orc War Chief"
subClass:
 - "CR 4"
cover: "Orc War Chief.png"
campaign:
locations:
tags:
  - race/orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/mm
---
###### Orc War Chief
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Orc War Chief.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 93 (11d8 + 44) |
> | :FasUserGroup: Race | Humanoid (orc) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 18 | 11 | 11 | 16 |
| **Mod** | +4 | +1 | +4 | +0 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Orc
**Saving Throws:** Str +6, Con +6, Wis +2
**Skills:** Intimidation +5

---

### Traits

**Aggressive.** As a bonus action, the orc can move up to its speed toward a hostile creature that it can see.

**Gruumsh's Fury.** The orc deals an extra 4 (1d8) damage when it hits with a weapon attack (included in the attacks).


---

### Actions

**Multiattack.** The orc makes two attacks with its greataxe or its spear.

**Greataxe.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 15 (1d12 + 4 plus 1d8) slashing damage.

**Spear.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 12 (1d6 + 4 plus 1d8) piercing damage, or 13 (2d8 + 4) piercing damage if used with two hands to make a melee attack.

**Battle Cry (1/Day).** Each creature of the war chief's choice that is within 30 feet of it, can hear it, and not already affected by Battle Cry gain advantage on attack rolls until the start of the war chief's next turn. The war chief can then make one attack as a bonus action.


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