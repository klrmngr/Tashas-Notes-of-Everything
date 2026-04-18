---
type: pc
race: "Humanoid (human)"
class:
 - "Molliver"
subClass:
 - "CR 3"
cover: "Molliver.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/wbtw
---
###### Molliver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Molliver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 (+1 leather armor) |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 17 | 16 | 10 | 9 | 16 |
| **Mod** | -1 | +3 | +3 | +0 | -1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** Common
**Saving Throws:** Dex +5, Int +2
**Skills:** Acrobatics +7, Sleight Of Hand +7, Stealth +7

---

### Traits

**Evasion.** When subjected to an effect that allows a Dexterity saving throw to take only half damage, Molliver takes no damage on a successful save or half damage on a failed one, provided Molliver is not incapacitated.

**Special Equipment.** Molliver wears +1 leather armor and boots of levitation.


---

### Actions

**Multiattack.** Molliver makes two Dagger or Shortsword attacks, or one of each.

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage. The attack deals an extra 7 (2d6) piercing damage if Molliver has advantage on the attack roll or if the target is within 5 feet of one of Molliver's allies.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 6 (1d6 + 3) piercing damage. The attack deals an extra 7 (2d6) piercing damage if Molliver has advantage on the attack roll or if the target is within 5 feet of one of Molliver's allies.

**Levitate.** While wearing boots of levitation, Molliver casts levitate (self only).


---

### Reactions

**Uncanny Dodge.** Molliver halves the damage they take from an attack made against them, provided they can see the attacker.


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