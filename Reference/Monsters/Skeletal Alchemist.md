---
type: pc
race: "Undead"
class:
 - "Skeletal Alchemist"
subClass:
 - "CR 1/2"
cover: "Skeletal Alchemist.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1-2
  - source/gos
---
###### Skeletal Alchemist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Skeletal Alchemist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 13 | 15 | 14 | 10 | 9 |
| **Mod** | -1 | +1 | +2 | +2 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands all languages it knew in life but can't speak
**Skills:** Arcana +4
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Magic Resistance.** The skeletal alchemist has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The skeletal alchemist makes two Lob Acid attacks.

**Claws.** Melee Weapon Attack: +3 to hit, reach 5 ft. one target. *Hit:* 4 (1d6 + 1) slashing damage.

**Lob Acid.** Ranged Weapon Attack: +3 to hit, range 30/120 ft., one target. *Hit:* 5 (1d8 + 1) acid damage.


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