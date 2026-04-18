---
type: pc
race: "Fiend"
class:
 - "Tooth-N-Claw"
subClass:
 - "CR 3"
cover: "Tooth-N-Claw.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/3
  - source/slw
---
###### Tooth-N-Claw
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SLW
___

> [!infobox|no-t right]
> ![[Tooth-N-Claw.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 45 (7d8 + 14) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | SLW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 14 | 6 | 13 | 6 |
| **Mod** | +3 | +1 | +2 | -2 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** understands Infernal but can't speak it
**Skills:** Perception +5
**Damage Immunities:** cold

---

### Traits

**Keen Hearing and Smell.** Tooth-N-Claw has advantage on Wisdom (Perception) checks that rely on hearing or smell.

**Pack Tactics.** Tooth-N-Claw has advantage on an attack roll against a creature if at least one of its allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 7 (2d6) cold damage.

**Freezing Breath (Recharge 5–6).** Tooth-N-Claw exhales an icy blast in a 15-foot cone. Each creature in that area must make a DC 12 Dexterity saving throw, taking 21 (6d6) cold damage on a failed save, or half as much damage on a successful one.


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