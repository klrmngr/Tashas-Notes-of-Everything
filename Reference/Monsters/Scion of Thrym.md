---
type: pc
race: "Giant (titan)"
class:
 - "Scion of Thrym"
subClass:
 - "CR 24"
cover: "Scion of Thrym.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/giant
  - size/gargantuan
  - cr/24
  - source/bgg
---
###### Scion of Thrym
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Scion of Thrym.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 24 (62,000 XP) |
> | :RiSwordFill: Type | Gargantuan Giant (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 499 (27d20 + 216) |
> | :FasUserGroup: Race | Giant (titan) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 16 | 27 | 17 | 20 | 21 |
| **Mod** | +10 | +3 | +8 | +3 | +5 | +5 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 22
**Languages:** Giant, Primordial
**Saving Throws:** Wis +12, Cha +12
**Skills:** Athletics +17, Perception +12
**Damage Resistances:** fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** cold
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified

---

### Traits

**Legendary Resistance (6/Day).** If the scion fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The scion has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The scion deals double damage to objects and structures.


---

### Actions

**Multiattack.** The scion makes one Ice Axe and two Slam attacks, or it makes two Glacier Throw attacks.

**Ice Axe.** Melee Weapon Attack: +17 to hit, reach 30 ft., one target. *Hit:* 36 (4d12 + 10) force damage plus 18 (4d8) cold damage.

**Slam.** Melee Weapon Attack: +17 to hit, reach 20 ft., one target. *Hit:* 32 (4d10 + 10) force damage.

**Glacier Throw.** Ranged Weapon Attack: +17 to hit, range 120/480 ft., one target. *Hit:* 36 (4d12 + 10) bludgeoning damage plus 14 (4d6) cold damage, and the target must succeed on a DC 25 Strength saving throw or have the prone condition.

**Glacial Upheaval (Recharge 5–6).** The scion digs its hands into the ground at a point it can see within 30 feet of itself and launches a magically conjured mass of ice into the air. Each creature other than the scion in a 30-foot-radius, 100-foot-high cylinder centered on that point must make a DC 25 Dexterity saving throw. On a failed save, a creature takes 36 (8d8) bludgeoning damage plus 19 (3d12) cold damage and is pushed vertically to the top of the cylinder, at which point the creature falls. On a successful save, a creature takes half as much damage and is pushed to the nearest unoccupied space outside the cylinder with no additional effects.
At the start of the scion's next turn, a mass of ice plummets to the ground on a point the scion can see within 60 feet of the point the scion dug its hands into. Each creature in a 30-foot-radius, 100-foot-high cylinder centered on that point must succeed on a DC 25 Dexterity saving throw or take 18 (4d8) bludgeoning damage plus 18 (4d8) cold damage.


---

### Bonus Actions

**Earth-Shaking Movement.** The scion moves up to its speed and sends a shock wave through the ground in a 60-foot-radius circle centered on itself. Each creature on the ground in that area that is concentrating must succeed on a DC 25 Constitution saving throw or lose concentration.


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