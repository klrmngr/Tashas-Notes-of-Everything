---
type: pc
race: "Fiend (demon)"
class:
 - "Hazvongel"
subClass:
 - "CR 14"
cover: "Hazvongel.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/14
  - source/veor
---
###### Hazvongel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Hazvongel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 237 (25d12 + 75) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 20 | 16 | 12 | 15 | 11 |
| **Mod** | +5 | +5 | +3 | +1 | +2 | +0 |

**Speed:** 20 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 17
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Con +8, Wis +7
**Skills:** Perception +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Magic Resistance.** The hazvongel has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The hazvongel makes three Talon attacks.

**Talon.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 18 (3d8 + 5) piercing damage.

**Blood Barrage (Recharge 5–6).** The hazvongel launches a spray of blood in a 90-foot cone. Each creature in that area must make a DC 18 Dexterity saving throw, taking 27 (6d8) necrotic damage on a failed save or half as much damage on a successful one.


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