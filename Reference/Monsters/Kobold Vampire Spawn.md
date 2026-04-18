---
type: pc
race: "Undead"
class:
 - "Kobold Vampire Spawn"
subClass:
 - "CR 3"
cover: "Kobold Vampire Spawn.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/3
  - source/idrotf
---
###### Kobold Vampire Spawn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Kobold Vampire Spawn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 39 (6d6 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 16 | 8 | 8 | 8 |
| **Mod** | +0 | +4 | +3 | -1 | -1 | -1 |

**Speed:** 30 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Draconic
**Saving Throws:** Dex +6, Wis +1
**Skills:** Perception +1, Stealth +6
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Pack Tactics.** The vampire has advantage on an attack roll against a creature if at least one of the vampire's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Regeneration.** The vampire regains 10 hit points at the start of its turn if it has at least 1 hit point and isn't in sunlight or running water. If the vampire takes radiant damage or damage from holy water, this trait doesn't function at the start of its next turn.

**Unusual Nature.** The vampire doesn't require air.

**Vampire Weaknesses.** The vampire has the following flaws:
- The vampire can't enter a residence without an invitation from one of the occupants.
- The vampire takes 20 acid damage when it starts its turn in running water.
- The vampire is destroyed if a piercing weapon made of wood is driven into its heart while it is incapacitated in its resting place.
- The vampire takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 6 (1d4 + 4) piercing damage plus 5 (2d4) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and the vampire regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.


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