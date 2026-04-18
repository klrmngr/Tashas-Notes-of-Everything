---
type: pc
race: "Fiend"
class:
 - "Mordakhesh"
subClass:
 - "CR 15"
cover: "Mordakhesh.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/15
  - source/erlw
---
###### Mordakhesh
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Mordakhesh.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 170 (20d8 + 80) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 18 | 15 | 17 | 20 |
| **Mod** | +5 | +3 | +4 | +2 | +3 | +5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 18
**Languages:** Common, Infernal
**Saving Throws:** Str +10, Con +9, Wis +8, Cha +10
**Skills:** Athletics +10, Insight +8, Perception +8, Persuasion +10
**Damage Vulnerabilities:** piercing from magic weapons wielded by good creatures
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered

---

### Traits

**Limited Magic Immunity.** Mordakhesh can't be affected or detected by spells of 6th level or lower unless he wishes to be. Mordakhesh has advantage on saving throws against all other spells and magical effects.


---

### Actions

**Multiattack.** Mordakhesh makes three greatsword attacks.

**Greatsword.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 5 (1d10) force damage.

**Chromatic Orb.** Ranged Spell Attack: +10 to hit, range 120 ft., one creature. *Hit:* 13 (3d8) damage of a type chosen by Mordakhesh: acid, cold, fire, lightning, poison, or thunder.


---

### Legendary Actions

### 

**Attack.** Mordakhesh makes one weapon attack or casts chromatic orb.

**Chromatic Resistance.** Modakhesh gains resistance to one damage type of his choice—acid, cold, fire, lightning, poison, or thunder—until the start of his next turn.

**Warlord's Command (Costs 2 Actions).** Mordakhesh targets up to two allies that he can see within 30 feet of him. If a target can see and hear him, the target can make one weapon attack as a reaction and gains advantage on the attack roll.


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