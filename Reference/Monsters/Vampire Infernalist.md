---
type: pc
race: "Undead (wizard)"
class:
 - "Vampire Infernalist"
subClass:
 - "CR 14"
cover: "Vampire Infernalist.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/undead
  - size/small
  - cr/14
  - source/abh
---
###### Vampire Infernalist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: ABH
___

> [!infobox|no-t right]
> ![[Vampire Infernalist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Small Undead (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 172 (23d8 + 69) |
> | :FasUserGroup: Race | Undead (wizard) |
> | :FasBook: Source | ABH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 17 | 20 | 16 | 18 |
| **Mod** | +4 | +3 | +3 | +5 | +3 | +4 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 18
**Languages:** Common, Infernal
**Saving Throws:** Con +8, Int +10
**Skills:** Arcana +10, Perception +8, Religion +10, Stealth +8
**Damage Resistances:** fire; necrotic; poison
**Condition Immunities:** poisoned

---

### Traits

**Legendary Resistance (3/Day, or 4/Day in Lair).** If the vampire fails a saving throw, it can choose to succeed instead.

**Misty Escape.** If the vampire drops to 0 Hit Points outside its resting place, the vampire uses Shape-Shift to become mist (no action required). If it can't use Shape-Shift, it is destroyed.
While it has 0 Hit Points in mist form, it can't return to its vampire form, and it must reach its resting place within 2 hours or be destroyed. Once in its resting place, it returns to its vampire form and has the Paralyzed condition until it regains any Hit Points, and it regains 1 Hit Point after spending 1 hour there.

**Vampire Weakness.** The vampire has these weaknesses:
- The vampire can't enter a residence without an invitation from an occupant.
- The vampire takes 20 Acid damage if it ends its turn in running water.
- If a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the Incapacitated condition in its resting place, the vampire has the Paralyzed condition until the weapon is removed.
- The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has Disadvantage on attack rolls and ability checks.


---

### Actions

**Multiattack (Vampire Form Only).** The vampire makes two Hellfire Claw attacks and uses Bite.

**Hellfire Claw (Vampire Form Only).** m +9, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage plus 10 (3d6) Fire damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 17) from one of two claws.

**Bite (Imp or Vampire Form Only).** con DC 18, one creature within 5 feet that is willing or that has the Grappled, Incapacitated, or Restrained condition.  6 (1d4 + 4) Piercing damage plus 16 (3d10) Necrotic damage and the creature loses its highest-level available spell slot (if any). The target's Hit Point maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains Hit Points equal to that amount. A Humanoid reduced to 0 Hit Points by this damage and then buried rises the following sunset as a Vampire Spawn under the vampire's control.


---

### Bonus Actions

**Shape-Shift.** If the vampire isn't in sunlight or running water, it shape-shifts into a Tiny imp (Speed 20 ft., Fly Speed 40 ft.), or a Medium cloud of mist (Speed 5 ft., Fly Speed 20 ft. [hover]), or it returns to its vampire form. Anything it is wearing transforms with it.
While in imp form, the vampire's game statistics, other than its size and Speed, are unchanged.
While in mist form, the vampire can't take any actions, speak, or manipulate objects. It is weightless and can enter an enemy's space and stop there. If air can pass through a space, the mist can do so, but it can't pass through liquid. It has Resistance to all damage, except the damage it takes from sunlight.


---

### Legendary Actions

### 

**Hellfire Strike.** The vampire moves up to half its Speed, and it makes one Hellfire Claw attack.

**Infernal Majesty.** cha DC 17, each creature in a 20-foot Emanation originating from the vampire.  9 (2d8) Psychic damage, and the target has the Frightened condition until the start of its next turn.  Half damage only.  The vampire can't take this action again until the start of its next turn.

**Teleport.** The vampire teleports up to 30 feet to an unoccupied space it can see.


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