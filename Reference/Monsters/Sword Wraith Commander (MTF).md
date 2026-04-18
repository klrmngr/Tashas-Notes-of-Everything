---
type: pc
race: "Undead"
class:
 - "Sword Wraith Commander"
subClass:
 - "CR 8"
cover: "Sword Wraith Commander.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/8
  - source/mtf
---
###### Sword Wraith Commander
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Sword Wraith Commander.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (breastplate, shield) |
> | :FasHeart: HP | 127 (15d8 + 60) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 18 | 11 | 12 | 14 |
| **Mod** | +4 | +2 | +4 | +0 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** the languages it knew in life
**Skills:** Perception +4
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; frightened; poisoned; unconscious

---

### Traits

**Martial Fury.** As a bonus action, the sword wraith can make one weapon attack, which deals an extra 9 (2d8) necrotic damage on a hit. If it does so, attack rolls against it have advantage until the start of its next turn.

**Turning Defiance.** The sword wraith and any other sword wraiths within 30 feet of it have advantage on saving throws against effects that turn undead.


---

### Actions

**Multiattack.** The sword wraith makes two weapon attacks.

**Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.

**Call to Honor (1/Day).** To use this action, the sword wraith must have taken damage during the current combat. If the sword wraith can use this action, it gives itself advantage on attack rolls until the end of its next turn, and 1d4 + 1 sword wraith warriors appear in unoccupied spaces within 30 feet of it. The warriors last until they drop to 0 hit points, and they take their turns immediately after the commander's turn on the same initiative count.


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