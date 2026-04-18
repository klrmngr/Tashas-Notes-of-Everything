---
type: pc
race: "Undead"
class:
 - "Vampire Warden"
subClass:
 - "CR 10"
cover: "Vampire Warden.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/10
  - source/abh
---
###### Vampire Warden
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: ABH
___

> [!infobox|no-t right]
> ![[Vampire Warden.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 190 (21d8 + 96) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | ABH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 15 | 18 | 10 | 14 | 17 |
| **Mod** | +5 | +2 | +4 | +0 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 20
**Languages:** Common
**Saving Throws:** Con +8, Wis +6
**Skills:** Athletics +9, Perception +10
**Damage Resistances:** necrotic
**Condition Immunities:** exhaustion; frightened

---

### Traits

**Magic Resistance.** The vampire has Advantage on saving throws against spells and other magical effects.

**Vampire Weakness.** The vampire has these weaknesses:
- The vampire can't enter a residence without an invitation from an occupant.
- The vampire takes 20 Acid damage if it ends its turn in running water.
- If a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the Incapacitated condition, the vampire has the Paralyzed condition until the weapon is removed.
- The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has Disadvantage on attack rolls and ability checks.
- If the vampire drops to 0 Hit Points while it doesn't have the Petrified condition, it turns to stone, regains 50 Hit Points, and has the Petrified condition for 1 hour.


---

### Actions

**Multiattack.** The vampire makes two Claw attacks and uses Bite or Guardian's Command.

**Claw.** m +9, reach 5 ft. *Hit:* 14 (2d8 + 5) Slashing damage plus 7 (2d6) Necrotic damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 16) from one of two claws.

**Bite.** con DC 16, one creature within 5 feet that is willing or that has the Grappled, Incapacitated, or Restrained condition.  7 (1d4 + 5) Piercing damage plus 7 (2d6) Necrotic damage. The target's Hit Point maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains Hit Points equal to that amount.


---

### Reactions

**Resilient Flesh.**  The vampire is hit by a melee attack roll from an attacker the vampire can see.  The vampire reduces the damage it takes from the attack by 11 (2d6 + 4).


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