---
type: pc
race: "Undead"
class:
 - "Tloques-Popolocas"
subClass:
 - "CR 5"
cover: "Tloques-Popolocas.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/5
  - source/tftyp
---
###### Tloques-Popolocas
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Tloques-Popolocas.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 16 | 11 | 10 | 12 |
| **Mod** | +3 | +3 | +3 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** the languages it knew in life
**Saving Throws:** Dex +6, Wis +3
**Skills:** Perception +3, Stealth +6
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Regeneration.** The vampire regains 10 hit points at the start of its turn if it has at least 1 hit point and isn't in sunlight or running water. If the vampire takes radiant damage or damage from holy water, this trait doesn't function at the start of the vampire's next turn.

**Spider Climb.** The vampire can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Vampire Weaknesses.** The vampire has the following flaws:
- The vampire can't enter a residence without an invitation from one of the occupants.
- The vampire takes 20 acid damage when it ends its turn in running water.
- The vampire is destroyed if a piercing weapon made of wood is driven into its heart while it is incapacitated in its resting place.
- The vampire takes 20 radiant damage when it starts its turn in sunlight. While in sunlight, it has disadvantage on attack rolls and ability checks.

**Shapechanger.** If the vampire isn't in sunlight or running water, it can use its action to Polymorph into a Tiny bat, or back into its true form.
While in bat form, the vampire can't speak, its walking speed is 5 feet, and it has a flying speed of 30 feet. Its Statistics, other than its size and speed, are unchanged. Anything it is wearing transforms with it, but nothing it is carrying does. It reverts to its true form if it dies.


---

### Actions

**Multiattack.** The vampire makes two attacks.

**Claws.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 8 (2d4 + 3) slashing damage. Instead of dealing damage, the vampire can grapple the target, escape DC 13.

**Children of the Night (1/Day).** The vampire magically calls 2d4 swarms of bats, provided that the sun isn't up. The called creatures arrive in 1d4 rounds, acting as allies of the vampire and obeying its spoken commands. The beasts remain for 1 hour, until the vampire dies, or until the vampire dismisses them as a bonus action.

**Tloques' Berserker Axe +2.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) slashing damage.


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