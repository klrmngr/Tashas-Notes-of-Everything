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
  - source/mpmm
---
###### Leviathan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
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
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 24 | 30 | 2 | 18 | 17 |
| **Mod** | +8 | +7 | +10 | -4 | +4 | +3 |

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

**Siege Monster.** The leviathan deals double damage to objects and structures.

**Water Form.** The leviathan can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing.


---

### Actions

**Multiattack.** The leviathan makes one Slam attack and one Tail attack.

**Slam.** Melee Weapon Attack: +14 to hit, reach 20 ft., one target. *Hit:* 21 (2d12 + 8) bludgeoning damage plus 13 (2d12) acid damage.

**Tail.** Melee Weapon Attack: +14 to hit, reach 20 ft., one target. *Hit:* 19 (2d10 + 8) bludgeoning damage plus 10 (3d6) acid damage.

**Tidal Wave (Recharge 6).** The leviathan magically creates a wave of water that extends from a point it can see within 120 feet of itself. The wave is up to 250 feet long, up to 250 feet tall, and up to 50 feet wide. Each creature in the wave must make a DC 24 Strength saving throw. On a failed save, a creature takes 45 (7d12) bludgeoning damage and is knocked prone. On a successful save, a creature takes half as much damage and isn't knocked prone. The water spreads out across the ground in all directions, extinguishing unprotected flames in its area and within 250 feet of it, and then it vanishes.


---

### Legendary Actions

### 

**Move.** The leviathan moves up to its speed.

**Slam (Costs 2 Actions).** The leviathan makes one Slam attack.


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