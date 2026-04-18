---
type: pc
race: "Ooze"
class:
 - "Gray Ooze"
subClass:
 - "CR 1/2"
cover: "Gray Ooze.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/medium
  - cr/1-2
  - source/mm
---
###### Gray Ooze
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Gray Ooze.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Ooze |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 22 (3d8 + 9) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 6 | 16 | 1 | 6 | 2 |
| **Mod** | +1 | -2 | +3 | -5 | -2 | -4 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 8
**Languages:** —
**Skills:** Stealth +2
**Damage Resistances:** acid; cold; fire
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; prone

---

### Traits

**Amorphous.** The ooze can move through a space as narrow as 1 inch wide without squeezing.

**Corrode Metal.** Any nonmagical weapon made of metal that hits the ooze corrodes. After dealing damage, the weapon takes a permanent and cumulative −1 penalty to damage rolls. If its penalty drops to −5, the weapon is destroyed. Nonmagical ammunition made of metal that hits the ooze is destroyed after dealing damage.
The ooze can eat through 2-inch-thick, nonmagical metal in 1 round.

**False Appearance.** While the ooze remains motionless, it is indistinguishable from an oily pool or wet rock.


---

### Actions

**Pseudopod.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) bludgeoning damage plus 7 (2d6) acid damage, and if the target is wearing nonmagical metal armor, its armor is partly corroded and takes a permanent and cumulative −1 penalty to the AC it offers. The armor is destroyed if the penalty reduces its AC to 10.


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