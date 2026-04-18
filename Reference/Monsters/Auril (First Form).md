---
type: pc
race: "Monstrosity"
class:
 - "Auril (First Form)"
subClass:
 - "CR 9"
cover: "Auril (First Form).png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/9
  - source/idrotf
---
###### Auril (First Form)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Auril (First Form).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 95 (10d8 + 50) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 21 | 24 | 26 | 28 |
| **Mod** | +2 | +3 | +5 | +7 | +8 | +9 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 120 ft., passive Perception 26
**Languages:** all, telepathy 1000 ft.
**Saving Throws:** Con +9, Wis +12
**Skills:** Deception +13, Insight +12, Intimidation +13, Perception +16
**Damage Vulnerabilities:** radiant
**Damage Immunities:** cold; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; stunned

---

### Traits

**Divine Being.** Auril can't be surprised and can't be changed into another form against her will.

**Divine Rejuvenation.** When Auril drops to 0 hit points, her body turns to slush and melts away. Auril instantly reappears in her [[Auril (second form)|second form]], in an unoccupied space within 60 feet of where her first form disappeared. Her initiative count doesn't change.

**Legendary Resistance (2/Day in This Form).** If Auril fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Auril has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** Auril doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** Auril attacks twice with her talons.

**Talons.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 3 (1d6) cold damage.

**Touch of Frost.** Melee Spell Attack: +13 to hit, reach 5 ft., one creature. *Hit:* 13 (3d8) cold damage, and the target can't take reactions until the start of its next turn.

**Chromatic Orb.** Ranged Spell Attack: +13 to hit, range 90 ft., one creature. *Hit:* 13 (3d8) cold damage.


---

### Legendary Actions

### 

**Talons.** Auril attacks once with her talons.

**Teleport.** Auril teleports to an unoccupied space she can see within 30 feet of her.

**Touch of Frost (Costs 2 Actions).** Auril uses Touch of Frost.


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