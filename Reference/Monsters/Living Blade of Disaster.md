---
type: pc
race: "Construct"
class:
 - "Living Blade of Disaster"
subClass:
 - "CR 8"
cover: "Living Blade of Disaster.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/8
  - source/idrotf
---
###### Living Blade of Disaster
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Living Blade of Disaster.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 67 (9d6 + 36) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 19 | 6 | 10 | 3 |
| **Mod** | +0 | +3 | +4 | -2 | +0 | -4 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** blinded; deafened; exhaustion; grappled; paralyzed; petrified; poisoned; restrained; unconscious

---

### Traits

**Magic Resistance.** The living spell has advantage on saving throws against spells and other magical effects.

**Unfettered.** The living spell can move through any barrier, even a wall of magical force.

**Unusual Nature.** The living spell doesn't require air, food, drink, or sleep.


---

### Actions

**Force Blade.** Melee Spell Attack: +6 to hit, reach 5 ft., one target. *Hit:* 26 (4d12) force damage, unless the living spell rolled an 18 or higher on the d20 for the attack, in which case the attack is a critical hit that deals 78 (12d12) force damage instead.


---

### Reactions

**Preemptive Strike.** The living spell makes a melee attack against a creature that starts its turn within 5 feet of the living spell.


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