---
type: pc
race: "Fiend"
class:
 - "Sweettooth Horror"
subClass:
 - "CR 4"
cover: "Sweettooth Horror.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/4
  - source/mcv4ec
---
###### Sweettooth Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Sweettooth Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 58 (9d10 + 9) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 18 | 12 | 6 | 8 | 12 |
| **Mod** | +2 | +4 | +1 | -2 | -1 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** —
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Caramelization.** If the horror takes fire damage, it releases a sweet, mesmerizing scent. Each creature within 30 feet of the horror must succeed on a DC 11 Wisdom saving throw or have the charmed condition. A charmed creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Magic Resistance.** The horror has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The horror makes one Bite attack and two Candy Cane attacks.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage plus 10 (3d6) acid damage.

**Candy Cane.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage. If the target is a Large or smaller creature, the horror can choose to deal no damage; instead, the target has the prone condition, and the horror can pull the target up to 5 feet toward itself.


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