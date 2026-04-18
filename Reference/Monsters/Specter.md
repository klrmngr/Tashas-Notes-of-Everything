---
type: pc
race: "Undead"
class:
 - "Specter"
subClass:
 - "CR 1"
cover: "Specter.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1
  - source/mm
---
###### Specter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Specter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 14 | 11 | 10 | 10 | 11 |
| **Mod** | -5 | +2 | +0 | +0 | +0 | +0 |

**Speed:** 0 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands all languages it knew in life but can't speak
**Damage Resistances:** acid; cold; fire; lightning; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Incorporeal Movement.** The specter can move through other creatures and objects as if they were 3. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Sunlight Sensitivity.** While in sunlight, the specter has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Life Drain.** Melee Spell Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 10 (3d6) necrotic damage. The target must succeed on a DC 10 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken. This reduction lasts until the creature finishes a long rest. The target dies if this effect reduces its hit point maximum to 0.


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