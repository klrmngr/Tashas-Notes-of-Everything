---
type: pc
race: "Giant (titan)"
class:
 - "Scion of Stronmaus"
subClass:
 - "CR 27"
cover: "Scion of Stronmaus.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/giant
  - size/gargantuan
  - cr/27
  - source/bgg
---
###### Scion of Stronmaus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Scion of Stronmaus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 27 (105,000 XP) |
> | :RiSwordFill: Type | Gargantuan Giant (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 656 (32d20 + 320) |
> | :FasUserGroup: Race | Giant (titan) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 20 | 30 | 26 | 28 | 24 |
| **Mod** | +10 | +5 | +10 | +8 | +9 | +7 |

**Speed:** 60 ft., fly 80 ft. ((hover)), swim 80 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 27
**Languages:** Giant, Primordial
**Saving Throws:** Dex +13, Int +16
**Skills:** Arcana +16, History +16, Perception +17
**Damage Resistances:** cold; fire; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; thunder
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; prone

---

### Traits

**Flyby.** The scion doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Legendary Resistance (6/Day).** If the scion fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The scion has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The scion deals double damage to objects and structures.


---

### Actions

**Multiattack.** The scion makes one attack using Lightning Sword or Hailstone, as well as two Slam attacks.

**Lightning Sword.** Melee Weapon Attack: +18 to hit, reach 30 ft., one target. *Hit:* 36 (4d12 + 10) force damage plus 22 (4d10) lightning damage.

**Hailstone.** Ranged Weapon Attack: +18 to hit, range 120/480 ft., one target. *Hit:* 32 (4d10 + 10) bludgeoning damage plus 18 (4d8) cold damage, and the target must succeed on a DC 26 Strength saving throw or have the prone condition.

**Slam.** Melee Weapon Attack: +18 to hit, reach 20 ft., one target. *Hit:* 36 (4d12 + 10) force damage.


---

### Bonus Actions

**Vengeful Storm (Recharge 6).** The scion conjures a churning storm cloud in a 30-foot-radius, 10-foot-tall cylinder centered on a point within 120 feet of itself. The cloud's area is heavily obscured. The cloud lasts for 1 minute, until the scion dies, or when the scion uses this bonus action again.
When the cloud appears, and as a bonus action on later turns, the scion can move the cloud up to 30 feet and cause one of the following effects in a 30-foot-radius, 120-foot-high cylinder directly below it; the scion can't choose the same effect two rounds in a row:

**Acid Rain.** The cloud rains acid. Each creature in the cylinder must succeed on a DC 25 Constitution saving throw or be covered in acid for 1 minute or until a creature uses its action to remove the acid from itself or another creature. A creature covered in the acid takes 26 (4d12) acid damage at the start of each of its turns.

**Freezing Storm.** Shards of ice pelt down, and freezing wind fills the area. Each creature in the cylinder must succeed on a DC 25 Dexterity saving throw or take 28 (8d6) cold damage and be hindered by ice formations for 1 minute or until it or another creature within reach of it uses an action to break away the ice. A creature hindered by ice has its speed reduced to 0.

**Lightning Bolts.** Bolts of lightning strike down. Each creature in the cylinder must succeed on DC 25 Dexterity saving throw or take 18 (4d8) lightning damage and have the stunned condition until the end of its next turn.


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