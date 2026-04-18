---
type: pc
race: "Undead"
class:
 - "Topi"
subClass:
 - "CR 1/2"
cover: "Topi.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/1-2
  - source/ttp
---
###### Topi
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: TTP
___

> [!infobox|no-t right]
> ![[Topi.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | TTP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 15 | 12 | 6 | 10 | 5 |
| **Mod** | -2 | +2 | +1 | -2 | +0 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages it knew in life but can't speak
**Damage Resistances:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Turn Resistance.** The topi has advantage on saving throws against any effect that turns undead.

**Undead Fortitude.** If damage reduces the topi to 0 hit points, it must make a Constitution saving throw with a DC of 5+the damage taken, unless the damage is radiant or from a critical hit. On a success, the topi drops to 1 hit point instead.


---

### Actions

**Venomous Claws.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage plus 2 (1d4) poison damage, and the target must succeed on a DC 11 Constitution saving throw or be poisoned until the end of the target's next turn.


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