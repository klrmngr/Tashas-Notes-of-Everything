---
type: pc
race: "Elemental"
class:
 - "Eriflamme"
subClass:
 - "CR 28"
cover: "Eriflamme.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/28
  - source/coa
---
###### Eriflamme
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Eriflamme.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 28 (120,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 518 (28d20 + 224) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 11 | 26 | 5 | 10 | 10 |
| **Mod** | +10 | +0 | +8 | -3 | +0 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Int +5, Wis +8, Cha +8
**Skills:** Arcana +5, Athletics +18
**Damage Immunities:** fire; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the Eriflamme fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The Eriflamme has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The Eriflamme makes four Claw attacks. It can replace one of the attacks with a Bite attack.

**Claw.** Melee Weapon Attack: +18 to hit, reach 15 ft., one target. *Hit:* 20 (3d6 + 10) slashing damage plus 7 (2d6) fire damage.

**Bite.** Melee Weapon Attack: +18 to hit, reach 10 ft., one target. *Hit:* 24 (4d6 + 10) piercing damage plus 33 (6d10) fire damage.

**Reform.** All the Eriflamme's fire elementals vanish and the Eriflamme reappears in one of their spaces. The Eriflamme's hit points are equivalent to the combined hit points of the fire elementals.


---

### Reactions

**Split (2/Day).** As a reaction to taking damage, the Eriflamme can split into fire elementals and reduce the damage to 0. The Eriflamme can form up to 10 [[Fire Elemental|fire elementals]], splitting its remaining hit points between them. The fire elementals appear in spaces adjacent to or within the Eriflamme's old location, and all act on the Eriflamme's initiative. They gain a +5 bonus to attack rolls and have the Eriflamme's Reform action.


---

### Legendary Actions

### 

**Slam.** The Eriflamme makes a Claw attack, which deals force damage instead of slashing damage if it hits.

**Fireglide.** The Eriflamme moves up to half its speed. It can fly during this movement.

**Chomp (Costs 2 Actions).** The Eriflamme makes a Bite attack with advantage.


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