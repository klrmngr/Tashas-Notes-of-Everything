---
type: pc
race: "Undead"
class:
 - "Jiangshi"
subClass:
 - "CR 9"
cover: "Jiangshi.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/9
  - source/vrgr
---
###### Jiangshi
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Jiangshi.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 119 (14d8 + 56) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 3 | 18 | 17 | 14 | 12 |
| **Mod** | +4 | -4 | +4 | +3 | +2 | +1 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** any languages it knew in life
**Saving Throws:** Con +8, Int +7, Wis +6, Cha +5
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Jiangshi Weaknesses.** The jiangshi has the following flaws:
*Fear of Its Own Reflection.* If the jiangshi sees its own reflection, it immediately uses its reaction, if available, to move as far away from the reflection as possible.
*Susceptible to Holy Symbols.* While the jiangshi is wearing or touching a holy symbol, it automatically fails saving throws against effects that turn Undead.

**Unusual Nature.** The jiangshi doesn't require air.


---

### Actions

**Multiattack.** The jiangshi makes three Slam attacks and uses Consume Energy.

**Slam.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage.

**Consume Energy.** The jiangshi draws energy from a creature it can see within 30 feet of it. The target makes a DC 16 Constitution saving throw, taking 18 (4d8) necrotic damage on a failed save, or half as much damage on a successful one. The jiangshi regains hit points equal to the amount of necrotic damage dealt. After regaining hit points from this action, the jiangshi gains the following benefits for 7 days: its walking speed increases to 40 feet, and it gains a flying speed equal to its walking speed and can hover.
A Humanoid slain by this necrotic damage rises as a wight (see its entry in the Monster Manual) at the end of the jiangshi's turn. The wight acts immediately after the jiangshi in the initiative order. If this wight slays a Humanoid with its Life Drain, the wight transforms into a jiangshi 5 days later.

**Change Shape.** The jiangshi polymorphs into a Beast, a Humanoid, or an Undead that is Medium or Small or back into its true form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying is absorbed or borne by the new form (the jiangshi's choice). It reverts to its true form if it dies.


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