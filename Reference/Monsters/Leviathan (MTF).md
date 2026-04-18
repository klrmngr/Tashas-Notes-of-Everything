---
type: pc
race: "Elemental"
class:
 - "Leviathan"
subClass:
 - "CR 20"
cover: "Leviathan.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/20
  - source/mtf
---
###### Leviathan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Leviathan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 328 (16d20 + 160) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 24 | 30 | 2 | 18 | 17 |
| **Mod** | +10 | +7 | +10 | -4 | +4 | +3 |

**Speed:** 40 ft., swim 120 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** —
**Saving Throws:** Wis +10, Cha +9
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Legendary Resistance (3/Day).** If the leviathan fails a saving throw, it can choose to succeed instead.

**Partial Freeze.** If the leviathan takes 50 cold damage or more during a single turn, the leviathan partially freezes; until the end of its next turn, its speeds are reduced to 20 feet, and it makes attack rolls with disadvantage.

**Siege Monster.** The leviathan deals double damage to objects and structures (included in Tidal Wave).

**Water Form.** The leviathan can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.


---

### Actions

**Multiattack.** The leviathan makes two attacks: one with its slam and one with its tail.

**Slam.** Melee Weapon Attack: +16 to hit, reach 20 ft., one target. *Hit:* 15 (1d10 + 10) bludgeoning damage plus 5 (1d10) acid damage.

**Tail.** Melee Weapon Attack: +16 to hit, reach 20 ft., one target. *Hit:* 16 (1d12 + 10) bludgeoning damage plus 6 (1d12) acid damage.

**Tidal Wave (Recharge 6).** While submerged, the leviathan magically creates a wall of water centered on itself. The wall is up 250 feet long, up to 250 feet high, and up to 50 feet thick. When the wall appears, all other creatures within its area must each make a DC 24 Strength saving throw. A creature takes 33 (6d10) bludgeoning damage on failed save, or half as much damage on a successful one.
At the start of each of the leviathan's turns after the wall appears, the wall, along with any other creatures in it, moves 50 feet away from the leviathan. Any Huge or smaller creature inside the wall or whose space the wall enters when it moves must succeed on a DC 24 Strength saving throw or take 27 (5d10) bludgeoning damage. A creature takes this damage no more than once on a turn. At the end of each turn the wall moves, the wall's height is reduced by 50 feet, and the damage creatures take from the wall on subsequent rounds is reduced by 1d10. When the wall reaches 0 feet in height, the effect ends.
A creature caught in the wall can move by swimming. Because of the force of the wave, though, the creature must make a successful DC 24 Strength (Athletics) check to swim at all during that turn.


---

### Legendary Actions

### 

**Slam (Costs 2 Actions).** The leviathan makes one slam attack.

**Move.** The leviathan moves up to its speed.


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