---
type: pc
race: "Fiend (devil)"
class:
 - "Dispater"
subClass:
 - "CR 27"
cover: "Dispater.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/27
  - source/coa
---
###### Dispater
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Dispater.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 27 (105,000 XP) |
> | :RiSwordFill: Type | Large Fiend (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 21 (natural armor, wrought-iron tower) |
> | :FasHeart: HP | 412 (33d10 + 231) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 17 | 25 | 25 | 22 | 24 |
| **Mod** | +9 | +3 | +7 | +7 | +6 | +7 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 24
**Languages:** Celestial, Common, Draconic, Infernal, telepathy 120 ft.
**Saving Throws:** Str +17, Dex +11, Con +15, Int +15
**Skills:** Arcana +23, Insight +22, Intimidation +15, Perception +14, Persuasion +15, Stealth +11
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede Dispater's darkvision.

**Fear Aura.** When a creature starts their turn within 120 feet of Dispater, they must succeed on a DC 22 Wisdom saving throw or have the frightened condition until they leave the aura. A creature that succeeds on the saving throw is immune to this effect for 1 hour.

**Fiendish Regeneration.** Dispater regains 20 hit points at the start of his turn. If he takes radiant damage this trait doesn't function at the start of his next turn. Dispater dies only if he starts his turn with 0 hit points and is unable to regenerate.

**Legendary Resistance (3/Day).** If Dispater fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Dispater has advantage on saving throws against spells and other magical effects.

**Rust Metal.** Any nonmagical weapon or ammunition made of metal that hits Dispater corrodes. After its hit, the weapon or ammunition is destroyed.


---

### Actions

**Multiattack.** Dispater makes four attacks using his Wrought- Iron Tower, Iron Column, or a combination of the two. He can replace one of the attacks with Superheat Metal (if available).

**Wrought-Iron Tower.** Melee Weapon Attack: +20 to hit, reach 10 ft., one target. *Hit:* 21 (2d8 + 12) bludgeoning damage plus 7 (2d6) fire damage. Dispater may replace the bludgeoning damage with damage of a type that the target is vulnerable to instead.

**Iron Column.** Ranged Spell Attack: +15 to hit, range 60 ft., one target. *Hit:* 21 (2d8 + 12) bludgeoning damage plus 7 (2d6) fire damage. Dispater may replace the bludgeoning damage with damage of a type that the target is vulnerable to instead.

**Superheat Metal (Recharge 4–6).** Dispater targets a metal object he can see within 90 feet of him. The metal glows white-hot, burning all that touches it. If the object was held by a creature, the creature must succeed on a DC 23 Dexterity saving throw to drop the object or take 45 (10d8) fire damage. If the object is attached to a creature, or they couldn't feasibly drop it, they automatically fail the save. The object returns to room temperature at the end of Dispater's turn.

**Nail Spray (2/Day).** Dispater conjures a storm of iron nails and launches them forward in a 90-foot-long, 5-foot-wide line. All creatures within the line must make a DC 23 Dexterity saving throw, taking 40 (16d4) piercing damage on a failed save, or half as much damage on a successful one. Nails launched from this ability stick into soft surfaces or fall to the ground after the attack finishes.


---

### Legendary Actions

### 

**Staff.** Dispater makes a Wrought-Iron Tower attack.

**Flesh to Iron (Costs 2 Actions).** Melee Spell Attack: +15 to hit, reach 5 ft., one target. *Hit:* 40 (6d10 + 7) force damage, and the target must make a DC 23 Constitution saving throw. On a failed save, the target's flesh begins to harden, and the creature's movement speed is halved for 1 minute. If the creature is harmed by Flesh to Iron again, while still partly iron, the rest of the creature also turns to iron, killing them.

**Call Underling (Costs 3 Actions).** Dispater summons an allied [[Erinyes]] in an unoccupied space that he can see.


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