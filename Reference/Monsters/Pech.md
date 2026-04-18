---
type: pc
race: "Elemental"
class:
 - "Pech"
subClass:
 - "CR 4"
cover: "Pech.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/4
  - source/ditlcot
---
###### Pech
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DitLCoT
___

> [!infobox|no-t right]
> ![[Pech.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 82 (11d6 + 44) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | DitLCoT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 18 | 11 | 14 | 10 |
| **Mod** | +4 | +0 | +4 | +0 | +2 | +0 |

**Speed:** 30 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., tremorsense 120 ft., passive Perception 14
**Languages:** Common, Terran
**Saving Throws:** Con +6, Wis +4
**Skills:** Athletics +6, Perception +4, Survival +4
**Condition Immunities:** petrified

---

### Traits

**Magic Resistance.** The pech has advantage on saving throws against spells and other magical effects.

**Sunlight Sensitivity.** While in sunlight, the pech has disadvantage on attack rolls.


---

### Actions

**Multiattack.** The pech makes two Fortified Pickaxe attacks. If it hits a Large or smaller creature with both attacks, the target must succeed on a DC 14 Strength saving throw or have the prone condition.

**Fortified Pickaxe.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) force damage. If the target is a Construct or an object, the attack is automatically a critical hit.


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