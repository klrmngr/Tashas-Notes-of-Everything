---
type: pc
race: "Fiend (demon)"
class:
 - "Hezrou"
subClass:
 - "CR 8"
cover: "Hezrou.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/8
  - source/mm
---
###### Hezrou
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Hezrou.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Fiend (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 136 (13d10 + 65) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 17 | 20 | 5 | 12 | 13 |
| **Mod** | +4 | +3 | +5 | -3 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Abyssal, telepathy 120 ft.
**Saving Throws:** Str +7, Con +8, Wis +4
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The hezrou has advantage on saving throws against spells and other magical effects.

**Stench.** Any creature that starts its turn within 10 feet of the hezrou must succeed on a DC 14 Constitution saving throw or be poisoned until the start of its next turn. On a successful saving throw, the creature is immune to the hezrou's stench for 24 hours.


---

### Actions

**Multiattack.** The hezrou makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage.


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