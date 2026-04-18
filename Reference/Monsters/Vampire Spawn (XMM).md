---
type: pc
race: "Undead"
class:
 - "Vampire Spawn"
subClass:
 - "CR 5"
cover: "Vampire Spawn.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/small
  - cr/5
  - source/xmm
---
###### Vampire Spawn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Vampire Spawn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Undead |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 16 | 11 | 10 | 12 |
| **Mod** | +3 | +3 | +3 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Common plus one other language
**Saving Throws:** Dex +6, Wis +3
**Skills:** Perception +3, Stealth +6
**Damage Resistances:** necrotic

---

### Traits

**Spider Climb.** The vampire can climb difficult surfaces, including along ceilings, without needing to make an ability check.

**Vampire Weakness.** The vampire has these weaknesses:
- **Forbiddance.** The vampire can't enter a residence without an invitation from an occupant.
- **Running Water.** The vampire takes 20 Acid damage if it ends its turn in running water.
- **Stake to the Heart.** The vampire is destroyed if a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the Incapacitated condition.
- **Sunlight.** The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has Disadvantage on attack rolls and ability checks.


---

### Actions

**Multiattack.** The vampire makes two Claw attacks and uses Bite.

**Claw.** m +6, reach 5 ft. *Hit:* 8 (2d4 + 3) Slashing damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 13) from one of two claws.

**Bite.** con DC 14, one creature within 5 feet that is willing or that has the Grappled, Incapacitated, or Restrained condition.  5 (1d4 + 3) Piercing damage plus 10 (3d6) Necrotic damage. The target's Hit Point maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains Hit Points equal to that amount.


---

### Bonus Actions

**Deathless Agility.** The vampire takes the Dash or Disengage action.


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