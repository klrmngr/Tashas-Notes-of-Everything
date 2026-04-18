---
type: pc
race: "Fiend (devil)"
class:
 - "Moloch"
subClass:
 - "CR 21"
cover: "Moloch.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/21
  - source/mpmm
---
###### Moloch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Moloch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 253 (22d10 + 132) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 19 | 22 | 21 | 18 | 23 |
| **Mod** | +8 | +4 | +6 | +5 | +4 | +6 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 21
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Dex +11, Con +13, Wis +11, Cha +13
**Skills:** Deception +13, Intimidation +13, Perception +11
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If Moloch fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Moloch has advantage on saving throws against spells and other magical effects.

**Regeneration.** Moloch regains 20 hit points at the start of his turn. If he takes radiant damage, this trait doesn't function at the start of his next turn. Moloch dies only if he starts his turn with 0 hit points and doesn't regenerate.


---

### Actions

**Multiattack.** Moloch makes one Bite attack, one Claw attack, and one Many-Tailed Whip attack.

**Bite.** Melee Weapon Attack: +15 to hit, reach 5 ft., one target. *Hit:* 26 (4d8 + 8) fire damage.

**Claw.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 17 (2d8 + 8) force damage.

**Many-Tailed Whip.** Melee Weapon Attack: +15 to hit, reach 30 ft., one target. *Hit:* 13 (2d4 + 8) lightning damage plus 11 (2d10) thunder damage. If the target is a creature, it must succeed on a DC 24 Strength saving throw or be pulled up to 30 feet in a straight line toward Moloch.

**Breath of Despair (Recharge 5–6).** Moloch exhales in a 30-foot cube. Each creature in that area must succeed on a DC 21 Wisdom saving throw or take 27 (5d10) psychic damage, drop whatever it is holding, and become frightened of Moloch for 1 minute. While frightened in this way, a creature must take the Dash action and move away from Moloch by the safest available route on each of its turns, unless there is nowhere to move, in which case it needn't take the Dash action. If the creature ends its turn in a location where it doesn't have line of sight to Moloch, the creature can repeat the saving throw, ending the effect on itself on a success.

**Teleport.** Moloch teleports, along with any equipment he is wearing or carrying, up to 120 feet to an unoccupied space he can see.


---

### Legendary Actions

### 

**Attack.** Moloch makes one Bite, Claw, or Many-Tailed Whip attack.

**Teleport.** Moloch uses Teleport.

**Cast a Spell (Costs 2 Actions).** Moloch uses Spellcasting.


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