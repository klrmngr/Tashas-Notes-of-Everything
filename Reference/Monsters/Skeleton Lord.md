---
type: pc
race: "Undead"
class:
 - "Skeleton Lord"
subClass:
 - "CR 9"
cover: "Skeleton Lord.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/9
  - source/mabjov
---
###### Skeleton Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Skeleton Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 136 (16d8 + 64) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 18 | 18 | 12 | 12 |
| **Mod** | +5 | +2 | +4 | +4 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** all the languages it knew in life
**Damage Vulnerabilities:** bludgeoning from magical attacks
**Damage Resistances:** cold; necrotic
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Fear Aura.** Any creature hostile to the skeleton lord that starts its turn within 20 feet of the skeleton lord must make a DC 17 Wisdom saving throw, unless the skeleton lord is incapacitated. On a failed save, the creature has the frightened condition until the start of its next turn. If a creature's saving throw is successful, then the creature is immune to the skeleton lord's Fear Aura for the next 24 hours.

**Magic Resistance.** The skeleton lord has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The skeleton lord's weapon attacks are magical and gain a +1 bonus to attack and damage rolls (included in the attack).


---

### Actions

**Multiattack.** The skeleton lord makes three Greatsword attacks.

**Greatsword.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage.


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