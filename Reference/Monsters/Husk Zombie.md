---
type: pc
race: "Undead"
class:
 - "Husk Zombie"
subClass:
 - "CR 1"
cover: "Husk Zombie.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1
  - source/egw
---
###### Husk Zombie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Husk Zombie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 16 | 3 | 6 | 5 |
| **Mod** | +3 | +0 | +3 | -4 | -2 | -3 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** understands the languages it knew in life but can't speak
**Saving Throws:** Con +5, Wis +0
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Curse of the Husk.** A humanoid slain by a melee attack from the zombie revives as a husk zombie on its next turn.

**Undead Fortitude.** If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead.


---

### Actions

**Multiattack.** The zombie makes two claw attacks. For each of these attacks that reduces a creature to 0 hit points, the zombie can make an additional claw attack.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


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