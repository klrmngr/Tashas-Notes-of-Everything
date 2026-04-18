---
type: pc
race: "Fiend"
class:
 - "Nightmare Shepherd"
subClass:
 - "CR 11"
cover: "Nightmare Shepherd.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/11
  - source/mot
---
###### Nightmare Shepherd
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Nightmare Shepherd.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 133 (14d10 + 56) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 18 | 14 | 17 | 20 |
| **Mod** | +4 | +2 | +4 | +2 | +3 | +5 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Con +8, Wis +7
**Skills:** Arcana +6, Deception +9, Perception +7, Persuasion +9
**Damage Resistances:** cold; necrotic
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Aura of Nightmares.** Undead creatures within 30 feet of the shepherd gain a +5 bonus to attack and damage rolls. When any other creature that isn't undead or a construct starts its turn within 30 feet of the shepherd, that creature must succeed on a DC 17 Wisdom saving throw or take 11 (2d10) psychic damage.

**Magic Resistance.** The shepherd has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The shepherd makes two attacks: one with its claws and one with its staff.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage plus 16 (3d10) necrotic damage.

**Staff.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage, or 13 (2d8 + 4) bludgeoning damage if used with two hands, plus 26 (4d12) psychic damage.

**Herd the Underworld (Recharges after a Short or Long Rest).** The shepherd pulls twisted souls from the Underworld; 1d6 shadows (without Sunlight Weakness) arise in unoccupied spaces within 20 feet of the shepherd. The shadows act right after the shepherd on the same initiative count and fight until they're destroyed. They disappear when the shepherd dies.


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