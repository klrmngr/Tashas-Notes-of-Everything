---
type: pc
race: "Giant (titan)"
class:
 - "Scion of Memnor"
subClass:
 - "CR 26"
cover: "Scion of Memnor.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/giant
  - size/gargantuan
  - cr/26
  - source/bgg
---
###### Scion of Memnor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Scion of Memnor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Gargantuan Giant (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 656 (32d20 + 320) |
> | :FasUserGroup: Race | Giant (titan) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 18 | 30 | 24 | 22 | 26 |
| **Mod** | +10 | +4 | +10 | +7 | +6 | +8 |

**Speed:** 60 ft., fly 80 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 24
**Languages:** Giant, Primordial
**Saving Throws:** Dex +12, Cha +16
**Skills:** Arcana +15, Perception +14
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** thunder
**Condition Immunities:** charmed; frightened; paralyzed; petrified

---

### Traits

**Flyby.** The scion doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Legendary Resistance (6/Day).** If the scion fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The scion has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The scion deals double damage to objects and structures.


---

### Actions

**Multiattack.** The scion makes one attack using Cloud Morningstar or Wind Javelin, as well as two Slam attacks.

**Cloud Morningstar.** Melee Weapon Attack: +18 to hit, reach 30 ft., one target. *Hit:* 32 (4d10 + 10) force damage plus 22 (4d10) thunder damage.

**Wind Javelin.** Ranged Weapon Attack: +18 to hit, range 120/480 ft., one target. *Hit:* 42 (5d12 + 10) thunder damage, and the target must succeed on a DC 26 Strength saving throw or have the prone condition.

**Slam.** Melee Weapon Attack: +18 to hit, reach 20 ft., one target. *Hit:* 28 (4d8 + 10) force damage.

**Thunderous Vortex (Recharge 5–6).** The scion magically creates a vortex of wind in a 60-foot-radius sphere centered on a point it can see within 120 feet of itself. Each creature in the sphere must succeed on a DC 24 Strength saving throw or be pulled straight toward the sphere's center, ending in an unoccupied space as close as possible to the center. Then a burst of thunder erupts in a 30-foot-radius sphere centered on the same point. Each creature in that area takes 52 (8d12) thunder damage and must succeed on a DC 24 Constitution saving throw or have the stunned condition until the end of its next turn.


---

### Bonus Actions

**Fog of Deception.** The scion conjures a magical cloud that fills a 30-foot-radius sphere centered on a point it can see within 90 feet of itself. Each creature in that area must make a DC 24 Wisdom saving throw. On a failed save, a creature has the charmed condition until the end of its next turn. While it has the charmed condition, the creature must use its action to make a melee attack against a creature other than itself of the scion's choice. If no creature is within its reach, the affected creature makes a ranged attack against a creature of the scion's choice, throwing its weapon if necessary. On a successful save, a creature is immune to the scion's Fog of Deception for the next 24 hours.


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