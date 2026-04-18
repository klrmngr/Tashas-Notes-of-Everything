---
type: pc
race: "Elemental"
class:
 - "Cradle of the Frost Scion"
subClass:
 - "CR 24"
cover: "Cradle of the Frost Scion.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/24
  - source/bgg
---
###### Cradle of the Frost Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cradle of the Frost Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 499 (27d20 + 216) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 14 | 26 | 11 | 19 | 16 |
| **Mod** | +8 | +2 | +8 | +0 | +4 | +3 |

**Speed:** 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Giant, Primordial
**Saving Throws:** Wis +11, Cha +10
**Damage Resistances:** fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Awakening of the Scion.** The cradle is a container for the [[scion of Thrym]]. When the cradle drops to 0 hit points, its body shatters into shards of ice. The scion instantly appears in the space the cradle occupied and uses the cradle's initiative count.

**Legendary Resistance (5/Day).** If the cradle fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The cradle has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The cradle deals double damage to objects and structures.


---

### Actions

**Multiattack.** The cradle makes two Slam or Hurl Icicle attacks.

**Slam.** Melee Weapon Attack: +15 to hit, reach 20 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage plus 11 (2d10) cold damage.

**Hurl Icicle.** Ranged Weapon Attack: +15 to hit, range 120 ft., one target. *Hit:* 26 (4d8 + 8) piercing damage plus 9 (2d8) cold damage, and the target must succeed on a DC 23 Strength saving throw or have the prone condition.

**Freezing Breath (Recharge 5–6).** The cradle exhales a blast of frost in a 90-foot cone. Each creature in that area must make a DC 23 Constitution saving throw. On a failed save, a creature takes 52 (8d12) cold damage, and its speed is reduced to 0 until the end of its next turn. On a successful save, a creature takes half as much damage only. If this damage would reduce the target to 0 hit points, the target drops to 1 hit point instead and has the petrified condition, turning into a frozen statue.
If the statue takes bludgeoning damage, it shatters, killing the frozen creature. If the statue would take fire damage, it instead takes no damage and thaws, ending the petrification.


---

### Bonus Actions

**Chilling Mist.** The cradle magically conjures a cloud of chilling mist that fills a 30-foot-radius sphere centered on a point it can see within 90 feet of itself. The mist spreads around corners. Each creature in that area must succeed on a DC 19 Constitution saving throw or take 28 (8d6) cold damage and be unable to use reactions until the start of its next turn. The mist vanishes at the end of the cradle's turn.


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