---
type: pc
race: "Construct"
class:
 - "Helmed Horror"
subClass:
 - "CR 4"
cover: "Helmed Horror.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/4
  - source/mm
---
###### Helmed Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Helmed Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 60 (8d8 + 24) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 16 | 10 | 10 | 10 |
| **Mod** | +4 | +1 | +3 | +0 | +0 | +0 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 14
**Languages:** understands the languages of its creator but can't speak
**Skills:** Perception +4
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Damage Immunities:** force; necrotic; poison
**Condition Immunities:** blinded; charmed; deafened; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Magic Resistance.** The helmed horror has advantage on saving throws against spells and other magical effects.

**Spell Immunity.** The helmed horror is immune to three spells chosen by its creator. Typical immunities include fireball, heat metal, and lightning bolt.


---

### Actions

**Multiattack.** The helmed horror makes two longsword attacks.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.


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