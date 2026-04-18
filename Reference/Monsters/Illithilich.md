---
type: pc
race: "Undead"
class:
 - "Illithilich"
subClass:
 - "CR 22"
cover: "Illithilich.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/22
  - source/vgm
---
###### Illithilich
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Illithilich.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral Chaotic Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 16 | 20 | 14 | 16 |
| **Mod** | +0 | +3 | +3 | +5 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** Deep Speech, Undercommon, telepathy 120 ft.
**Saving Throws:** Con +10, Int +12, Wis +9
**Skills:** Arcana +19, History +12, Insight +9, Perception +9
**Damage Resistances:** cold; lightning; necrotic
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the illithilich fails a saving throw, it can choose to succeed instead.

**Rejuvenation.** If it has a phylactery, a destroyed illithilich gains a new body in 1d10 days, regaining all its hit points and becoming active again. The new body appears within 5 feet of the phylactery.

**Turn Resistance.** The illithilich has advantage on saving throws against any effect that turns undead.

**Magic Resistance.** The illithilich has advantage on saving throws against spells and other magical effects.


---

### Actions

**Paralyzing Touch.** Melee Spell Attack: +12 to hit, reach 5 ft., one creature. *Hit:* 10 (3d6) cold damage. The target must succeed on a DC 18 Constitution saving throw or be paralyzed for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Tentacles.** Melee Weapon Attack: +12 to hit, reach 5 ft., one creature. *Hit:* 21 (3d10 + 5) psychic damage. If the target is Large or smaller, it is grappled (escape DC 15) and must succeed on a DC 20 Intelligence saving throw or be stunned until this grapple ends.

**Extract Brain.** Melee Weapon Attack: +12 to hit, reach 5 ft., one incapacitated humanoid grappled by the lich. *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0 hit points, the lich kills the target by extracting and devouring its brain.

**Mind Blast (Recharge 5–6).** The illithilich magically emits psychic energy in a 60-foot cone. Each creature in that area must succeed on a DC 18 Intelligence saving throw or take 27 (5d8 + 5) psychic damage and be stunned for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Legendary Actions

### 

**Tentacles.** The illithilich makes one attack with its tentacles.

**Extract Brain (Costs 2 Actions).** The illithilich uses Extract Brain.

**Mind Blast (Costs 3 Actions).** The illithilich recharges its Mind Blast and uses it.

**Cast Spell (Costs 1–3 Actions).** The illithilich uses a spell slot to cast a 1st-, 2nd-, or 3rd-level spell that it has prepared. Doing so costs 1 legendary action per level of the spell.


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