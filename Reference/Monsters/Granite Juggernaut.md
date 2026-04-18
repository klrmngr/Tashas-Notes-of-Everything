---
type: pc
race: "Construct"
class:
 - "Granite Juggernaut"
subClass:
 - "CR 12"
cover: "Granite Juggernaut.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/12
  - source/veor
---
###### Granite Juggernaut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Granite Juggernaut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 157 (15d10 + 75) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 1 | 20 | 2 | 11 | 3 |
| **Mod** | +6 | -5 | +5 | -4 | +0 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 10
**Languages:** —
**Damage Immunities:** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; prone

---

### Traits

**Magic Resistance.** The juggernaut has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The juggernaut deals double damage to objects and structures.


---

### Actions

**Slam.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 11 (1d10 + 6) bludgeoning damage, and if the target is a Large or smaller creature, it must succeed on a DC 18 Strength saving throw or have the prone condition.


---

### Bonus Actions

**Devastating Roll.** The juggernaut moves up to its speed. During this movement, the juggernaut can move through the spaces of creatures with the prone condition. When the juggernaut enters the space of a prone creature for the first time during this movement, the creature must make a DC 18 Dexterity saving throw, taking 55 (10d10) bludgeoning damage on a failed save or half as much damage on a successful one.


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