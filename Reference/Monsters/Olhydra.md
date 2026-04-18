---
type: pc
race: "Elemental"
class:
 - "Olhydra"
subClass:
 - "CR 18"
cover: "Olhydra.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/huge
  - cr/18
  - source/pota
---
###### Olhydra
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Olhydra.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 18 (20,000 XP) |
> | :RiSwordFill: Type | Huge Elemental |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 324 (24d12 + 168) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 22 | 24 | 17 | 18 | 23 |
| **Mod** | +5 | +6 | +7 | +3 | +4 | +6 |

**Speed:** 50 ft., swim 100 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 14
**Languages:** Aquan
**Saving Throws:** Str +11, Con +13, Wis +10
**Damage Resistances:** lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; cold; poison
**Condition Immunities:** charmed; frightened; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Empowered Attacks.** Olhydra's slam attacks are treated as magical for the purpose of bypassing resistance and immunity to nonmagical attacks.

**Legendary Resistance (3/Day).** If Olhydra fails a saving throw, she can choose to succeed instead.

**Magic Resistance.** Olhydra has advantage on saving throws against spells and other magical effects.

**Water Form.** Olhydra can enter a hostile creature's space and stop there. She can move through a space as narrow as 1 inch wide without squeezing.


---

### Actions

**Multiattack.** Olhydra makes two slam attacks or two water jet attacks.

**Slam.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 21 (3d10 + 5) bludgeoning damage, and the target is grappled (escape DC 19). Olhydra can grapple up to four targets. When Olhydra moves, all creatures she is grappling move with her.

**Water Jet.** Ranged Weapon Attack: +12 to hit, range 120 ft., one target. *Hit:* 21 (6d6) bludgeoning damage, and the target is knocked prone if it fails a DC 19 Strength saving throw.

**Summon Elementals (1/Day).** Olhydra summons up to three [[Water Elemental|water elementals]] and loses 30 hit points for each elemental she summons. Summoned elementals have maximum hit points, appear within 100 feet of Olhydra, and disappear if Olhydra is reduced to 0 hit points.


---

### Legendary Actions

### 

**Crush.** One creature that Olhydra is grappling is crushed for 21 (3d10 + 5) bludgeoning damage.

**Fling (Costs 2 Actions).** Olhydra releases one creature she is grappling by flinging the creature up to 60 feet away from her, in a direction of her choice. If the flung creature comes into contact with a solid surface, such as a wall or floor, the creature takes 1d6 bludgeoning damage for every 10 feet it was flung.

**Water to Acid (Costs 3 Actions).** Olhydra transforms her watery body into acid. This effect lasts until Olhydra's next turn. Any creature that comes into contact with Olhydra or hits her with a melee attack while standing within 5 feet of her takes 11 (2d10) acid damage. Any creature grappled by Olhydra takes 22 (4d10) acid damage at the start of its turn.


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