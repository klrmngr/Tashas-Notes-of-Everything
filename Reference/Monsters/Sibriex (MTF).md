---
type: pc
race: "Fiend (demon)"
class:
 - "Sibriex"
subClass:
 - "CR 18"
cover: "Sibriex.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/huge
  - cr/18
  - source/mtf
---
###### Sibriex
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Sibriex.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Huge Fiend (demon) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 150 (12d12 + 72) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 3 | 23 | 25 | 24 | 25 |
| **Mod** | +0 | -4 | +6 | +7 | +7 | +7 |

**Speed:** 0 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** all, telepathy 120 ft.
**Saving Throws:** Int +13, Cha +13
**Skills:** Arcana +13, History +13, Perception +13
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Contamination.** The sibriex emits an aura of corruption 30 feet in every direction. Plants that aren't creatures wither in the aura, and the ground in it is 3 for other creatures. Any creature that starts its turn in the aura must succeed on a DC 20 Constitution saving throw or take 14 (4d6) poison damage. A creature that succeeds on the save is immune to this sibriex's Contamination for 24 hours.

**Legendary Resistance (3/Day).** If the sibriex fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The sibriex has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The sibriex uses Squirt Bile once and makes three attacks using its chain, bite, or both.

**Chain.** Melee Weapon Attack: +6 to hit, reach 15 ft., one target. *Hit:* 20 (2d12 + 7) piercing damage.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d8) piercing damage plus 9 (2d8) acid damage.

**Squirt Bile.** The sibriex targets one creature it can see within 120 feet of it. The target must succeed on a DC 20 Dexterity saving throw or take 35 (10d6) acid damage.

**Warp Creature.** The sibriex targets up to three creatures it can see within 120 feet of it. Each target must make a DC 20 Constitution saving throw. On a successful save, a creature becomes immune to this sibriex's Warp Creature. On a failed save, the target is poisoned, which causes it to also gain 1 level of exhaustion. While poisoned in this way, the target must repeat the saving throw at the start of each of its turns. Three successful saves against the poison end it, and ending the poison removes any levels of exhaustion caused by it. Each failed save causes the target to suffer another level of exhaustion. Once the target reaches 6 levels of exhaustion, it dies and instantly transforms into a living [[Abyssal Wretch]] under the sibriex's control. The transformation of the body can be undone only by a wish spell.


---

### Legendary Actions

### 

**Cast a Spell.** The sibriex casts a spell.

**Spray Bile.** The sibriex uses Squirt Bile.

**Warp (Costs 2 Actions).** The sibriex uses Warp Creature.


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