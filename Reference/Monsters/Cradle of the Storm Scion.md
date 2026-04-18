---
type: pc
race: "Elemental"
class:
 - "Cradle of the Storm Scion"
subClass:
 - "CR 27"
cover: "Cradle of the Storm Scion.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/27
  - source/bgg
---
###### Cradle of the Storm Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cradle of the Storm Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 27 (105,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 682 (35d20 + 315) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 14 | 29 | 16 | 23 | 18 |
| **Mod** | +10 | +2 | +9 | +3 | +6 | +4 |

**Speed:** 40 ft., fly 60 ft. ((hover)), swim 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Giant, Primordial
**Damage Resistances:** cold; fire; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Awakening of the Scion.** The cradle is a container for the scion of Stronmaus. When the cradle drops to 0 hit points, its body bursts into light. The scion instantly appears in the space the cradle occupied and uses the cradle's initiative count.

**Legendary Resistance (5/Day).** If the cradle fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The cradle has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The cradle deals double damage to objects and structures.


---

### Actions

**Multiattack.** The cradle makes three Slam or Spit Hailstone attacks in any combination.

**Slam.** Melee Weapon Attack: +18 to hit, reach 20 ft., one target. *Hit:* 36 (4d12 + 10) bludgeoning damage plus 19 (3d12) lightning damage.

**Spit Hailstone.** Ranged Weapon Attack: +18 to hit, range 120 ft., one target. *Hit:* 32 (4d10 + 10) bludgeoning damage plus 14 (4d6) cold damage, and the target must succeed on a DC 26 Strength saving throw or have the prone condition.

**Lightning Barrage (Recharge 5–6).** The cradle hurls multiple magical lightning bolts at up to two creatures it can see within 500 feet of itself. Each target must make a DC 22 Dexterity saving throw. On a failed save, the target takes 71 (11d12) lightning damage and has the stunned condition until the end of its next turn. On a successful save, the target takes half as much damage only.


---

### Reactions

**Booming Step.** Immediately after taking damage, the cradle cracks with thunder and then magically teleports up to 60 feet to an unoccupied space it can see. Each creature within 10 feet of the space the cradle left must make a DC 22 Constitution saving throw, taking 14 (4d6) thunder damage on a failed save, or half as much damage on a successful one.


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