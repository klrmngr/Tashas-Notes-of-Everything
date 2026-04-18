---
type: pc
race: "Humanoid (tiefling)"
class:
 - "Eo Ashmajiir"
subClass:
 - "CR 11"
cover: "Eo Ashmajiir.png"
campaign:
locations:
tags:
  - race/tiefling
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/11
  - source/mabjov
---
###### Eo Ashmajiir
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Eo Ashmajiir.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (tiefling) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 126 (28d8 + 0) |
> | :FasUserGroup: Race | Humanoid (tiefling) |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 10 | 12 | 14 | 20 |
| **Mod** | +0 | +3 | +0 | +1 | +2 | +5 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Abyssal, Celestial, Common, Draconic, Infernal, Undercommon
**Saving Throws:** Con +4, Cha +9
**Skills:** Arcana +9, Deception +9, Persuasion +9
**Damage Resistances:** lightning

---

### Traits

**Lightning Affinity.** When Eo uses Spellcasting to cast a spell that deals lightning damage, that spell deals an additional 5 damage. When Eo casts a spell that deals a type of damage from the following list, she can change that damage type to lightning: acid, cold, fire, poison, thunder.


---

### Actions

**Twinned Orbs.** Melee or Ranged Spell Attack: +9 to hit, reach 5 ft. or range 90 ft., two targets. *Hit:* 27 (5d8 + 5) acid, cold, fire, lightning, poison or thunder damage (Eo's choice).

**Twinned Spell.** Eo uses Spellcasting to cast banishment, dominate person, finger of death, or power word stun. This spell targets a second creature in range.

**Discharge (1/Day).** Eo emits a thin green ray at a creature within 60 feet. The target must make a DC 17 Dexterity saving throw. On a failed save the target takes 89 (14d6 + 40) force damage. If this damage reduces the target to 0 hit points, it is disintegrated. A disintegrated creature and everything it is wearing and carrying, except magic items, are reduced to a pile of fine gray dust. The creature can be restored to life only by means of a true resurrection or a wish spell.


---

### Reactions

**Shocking Rebuke.** As a reaction to taking damage, Eo surrounds her attacker with a coil of lightning. The target must make a DC 17 Dexterity saving throw. It takes 16 (2d10 + 5) lightning damage on a failed save, half as much damage on a successful one.


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