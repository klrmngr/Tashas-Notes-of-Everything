---
type: pc
race: "Fiend (devil)"
class:
 - "Bel"
subClass:
 - "CR 25"
cover: "Bel.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/25
  - source/coa
---
###### Bel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Bel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 364 (27d10 + 216) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 14 | 26 | 25 | 19 | 26 |
| **Mod** | +9 | +2 | +8 | +7 | +4 | +8 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 14
**Languages:** Common, Infernal, telepathy 120 ft.
**Saving Throws:** Dex +10, Con +16, Wis +12
**Skills:** Arcana +15, Deception +16, Insight +12, Persuasion +16
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Fear Aura.** Any creature hostile to Bel that starts its turn within 20 feet of him must make a DC 23 Wisdom saving throw unless Bel is incapacitated. If the save fails, the creature has the frightened condition until the start of its next turn. If a creature's saving throw is successful, the creature is immune to Bel's Fear Aura for the next 24 hours.

**Legendary Resistance (3/Day).** If Bel fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Bel has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Bel attacks twice with his Greatsword and once with his Tail.

**Greatsword.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 23 (4d6 + 9) slashing damage plus 21 (6d6) fire damage. If the target is a flammable object that isn't being held or worn, it catches fire.

**Tail.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 25 (3d10 + 9) bludgeoning damage. If the target is a creature, it must succeed on a DC 23 Constitution saving throw or have the stunned condition until the end of its next turn.


---

### Legendary Actions

### 

**Fireball.** Bel casts Fireball.

**Tactical Edge (Costs 2 Actions).** Roll a d6 for Bel. The number rolled on the die is subtracted from the next attack roll made against Bel or an ally of his choice within the next minute.

**Summon Ice Devil (Costs 3 Actions).** Bel magically summons an [[Ice Devil]] with an ice spear (as described in the ice devil's entry in the Monster Manual). The ice devil appears in an unoccupied space within 60 feet of Bel, acts as Bel's ally, and can summon other devils if it has such power. The ice devil remains until Bel dies or until he dismisses it with an action.


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