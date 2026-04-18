---
type: pc
race: "Elemental"
class:
 - "Cradle of the Cloud Scion"
subClass:
 - "CR 26"
cover: "Cradle of the Cloud Scion.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/26
  - source/bgg
---
###### Cradle of the Cloud Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cradle of the Cloud Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 26 (90,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 624 (32d20 + 288) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 21 | 28 | 14 | 22 | 19 |
| **Mod** | +9 | +5 | +9 | +2 | +6 | +4 |

**Speed:** 0 ft., fly 90 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Giant, Primordial
**Saving Throws:** Int +10, Cha +12
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison; thunder
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Awakening of the Scion.** The cradle is a container for the scion of Memnor. When the cradle drops to 0 hit points, its body dissipates into cloud wisps. The scion instantly appears in the space the cradle occupied and uses the cradle's initiative count.

**Flyby.** The cradle doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Legendary Resistance (5/Day).** If the cradle fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The cradle has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The cradle deals double damage to objects and structures.


---

### Actions

**Multiattack.** The cradle makes three Slam or Wind Javelin attacks in any combination.

**Slam.** Melee Weapon Attack: +17 to hit, reach 20 ft., one target. *Hit:* 31 (4d10 + 9) bludgeoning damage plus 19 (3d12) thunder damage.

**Wind Javelin.** Ranged Weapon Attack: +17 to hit, range 120 ft., one target. *Hit:* 27 (4d8 + 9) bludgeoning damage plus 10 (3d6) thunder damage, and the target must succeed on a DC 25 Strength saving throw or have the prone condition.

**Vortex (Recharge 5–6).** The cradle conjures a vortex of wind at a point it can see within 90 feet of itself. The wind vortex is a 30-foot-radius, 100-foot-high cylinder centered on that point. Each creature other than the cradle in that area must make a DC 25 Dexterity saving throw. On a failed save, a creature takes 71 (11d12) bludgeoning damage and has the restrained condition within the vortex. On a successful save, a creature takes half as much damage and is pushed to the nearest unoccupied space outside the cylinder. The vortex lasts until the start of the cradle's next turn. A creature with the restrained condition falls prone when the vortex ends.
A creature with the restrained condition can use its action to try to escape the vortex. The creature makes a DC 19 Strength (Athletics) or Dexterity (Acrobatics) check. On a successful check, the creature escapes and moves 3d6 × 10 feet away from the vortex in a random direction.


---

### Reactions

**Thunderclap.** Immediately after taking damage, the cradle unleashes a thunderclap in a 30-foot-radius sphere centered on itself. All other creatures in that area must succeed on a DC 25 Constitution saving throw or take 18 (4d8) thunder damage and have the deafened condition for 1 minute.


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