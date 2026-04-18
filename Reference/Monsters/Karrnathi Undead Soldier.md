---
type: pc
race: "Undead"
class:
 - "Karrnathi Undead Soldier"
subClass:
 - "CR 3"
cover: "Karrnathi Undead Soldier.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/erlw
---
###### Karrnathi Undead Soldier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Karrnathi Undead Soldier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (half plate armor) |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 12 | 13 | 5 |
| **Mod** | +3 | +2 | +3 | +1 | +1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common
**Skills:** Athletics +5, Perception +3
**Damage Resistances:** cold; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Pack Tactics.** The soldier has advantage on an attack roll against a creature if at least one of the soldier's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Undead Fortitude.** If damage reduces the soldier to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the soldier drops to 1 hit point instead.


---

### Actions

**Multiattack.** The soldier attacks three times with one of its weapons.

**Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


---

### Reactions

**Parry.** The soldier adds 3 to its AC against one melee attack that would hit it. To do so, the soldier must see the attacker and be wielding a melee weapon.


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