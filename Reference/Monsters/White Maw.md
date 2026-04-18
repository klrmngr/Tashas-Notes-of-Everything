---
type: pc
race: "Ooze"
class:
 - "White Maw"
subClass:
 - "CR 10"
cover: "White Maw.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/gargantuan
  - cr/10
  - source/tftyp
---
###### White Maw
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[White Maw.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Gargantuan Ooze |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 5 |
> | :FasHeart: HP | 217 (14d20 + 70) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 1 | 20 | 12 | 10 | 3 |
| **Mod** | +4 | -5 | +5 | +1 | +0 | -4 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 10
**Languages:** telepathy 50 ft.
**Damage Resistances:** acid; cold; fire
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; poisoned; prone

---

### Traits

**Amorphous Form.** White Maw can occupy another creature's space and vice versa.

**Corrode Metal.** Any nonmagical weapon made of metal that hits White Maw corrodes. After dealing damage, the weapon takes a permanent and cumulative −1 penalty to damage rolls. if its penalty drops to −5, the weapon is destroyed. Nonmagical ammunition made of metal that hits White Maw is destroyed after dealing damage.
White Maw can eat through 2-inch-thick, nonmagical metal in 1 round.

**False Appearance.** While White Maw remains motionless, it is indistinguishable from white stone.

**Killer Response.** Any creature that starts its turn in White Maw's space is targeted by a pseudopod attack if White Maw isn't incapacitated.


---

### Actions

**Pseudopod.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 22 (4d8 + 4) bludgeoning damage plus 9 (2d8) acid damage. If the target is wearing nonmagical metal armor, its armor is partly corroded and takes a permanent and cumulative −1 penalty to the AC it offers. The armor is destroyed if the penalty reduces its AC to 10.


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