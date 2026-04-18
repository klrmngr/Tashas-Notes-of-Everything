---
type: pc
race: "Fiend"
class:
 - "Rak Tulkhesh"
subClass:
 - "CR 28"
cover: "Rak Tulkhesh.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/28
  - source/erlw
---
###### Rak Tulkhesh
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Rak Tulkhesh.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 28 (120,000 XP) |
> | :RiSwordFill: Type | Huge Fiend |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 23 (natural armor); 25 versus ranged attacks |
> | :FasHeart: HP | 478 (33d12 + 264) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 19 | 27 | 21 | 22 | 26 |
| **Mod** | +9 | +4 | +8 | +5 | +6 | +8 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Str +17, Con +16, Wis +14, Cha +16
**Skills:** Athletics +17, Intimidation +16, Perception +14
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned; stunned

---

### Traits

**Deadly Critical.** Rak Tulkhesh scores a critical hit on a roll of 19 or 20 and rolls the damage dice three times, instead of twice.

**Legendary Resistance (3/Day).** If Rak Tulkhesh fails a saving throw, he can choose to succeed instead.

**Magic Resistance.** Rak Tulkhesh has advantage on saving throws against spells and other magical effects.

**Whirlwind of Weapons.** A magical aura of weapons surrounds Rak Tulkhesh in a 10 foot radius. At the start of each of his turns, any other creature in the aura takes 14 (4d6) force damage.


---

### Actions

**Multiattack.** Rak Tulkhesh makes four weapon attacks.

**Spawned Melee Weapon.** Melee Weapon Attack: +17 to hit, reach 10 ft., one target. *Hit:* 28 (3d12 + 9) force damage.

**Spawned Ranged Weapon.** Ranged Weapon Attack: +12 to hit, range 150/600 ft., one target. *Hit:* 17 (3d8 + 4) force damage.

**Change Shape.** Rak Tulkhesh magically polymorphs into a humanoid, beast, or giant that has a challenge rating no higher than his own, or back into his true form. He reverts to his true form if he dies. Any equipment he is wearing or carrying is absorbed or borne by the new form (his choice).
In a new form, Rak Tulkhesh retains his alignment, hit points, Hit Dice, ability to speak, proficiencies, Legendary Resistance, and Intelligence, Wisdom, and Charisma scores, as well as this action. His statistics and capabilities are otherwise replaced by those of the new form, except any class features or legendary actions of that form.


---

### Legendary Actions

### 

**Attack.** Rak Tulkhesh makes one weapon attack.

**End Magic (Costs 2 Actions).** Rak Tulkhesh casts dispel magic.

**Provoke Rage (Costs 3 Actions).** Each creature within 60 feet of Rak Tulkhesh must succeed on a DC 24 Wisdom saving throw or use its reaction to make a melee weapon attack against a random creature within reach. If no creatures are within reach, it makes a ranged weapon attack against a random creature within range, throwing its weapon if necessary. This attack is made with advantage and gains a +4 bonus to the damage roll.


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