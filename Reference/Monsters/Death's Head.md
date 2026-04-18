---
type: pc
race: "Undead"
class:
 - "Death's Head"
subClass:
 - "CR 1/2"
cover: "Death's Head.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/1-2
  - source/vrgr
---
###### Death's Head
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Death's Head.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 17 (5d4 + 5) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 13 | 12 | 5 | 14 | 3 |
| **Mod** | -1 | +1 | +1 | -3 | +2 | -4 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** —
**Damage Resistances:** necrotic

---

### Traits

**Beheaded Form.** When created, a death's head takes one of three forms: Aberrant Head, Gnashing Head, or Petrifying Head. This form determines the creature's attack.

**Unusual Nature.** The death's head doesn't require air, food, drink, or sleep.


---

### Actions

**Gnashing Bite (Gnashing Head Only).** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage plus 7 (2d6) necrotic damage.

**Mind-Bending Bite (Aberrant Head Only).** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage plus 5 (1d10) necrotic damage, and the target must succeed on a DC 10 Intelligence saving throw or it can't take a reaction until the end of its next turn. Moreover, on its next turn, the target must choose whether it gets a move, an action, or a bonus action; it gets only one of the three.

**Petrifying Bite (Petrifying Head Only).** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage, and the target must succeed on a DC 10 Constitution saving throw or be restrained as it begins to turn to stone. The target must repeat the saving throw at the end of its next turn. On a success, the effect ends. On a failure, the target is petrified for 10 minutes.


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