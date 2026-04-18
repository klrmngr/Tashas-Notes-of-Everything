---
type: pc
race: "Elemental"
class:
 - "Cradle of the Hill Scion"
subClass:
 - "CR 22"
cover: "Cradle of the Hill Scion.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/22
  - source/bgg
---
###### Cradle of the Hill Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cradle of the Hill Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 402 (23d20 + 161) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 24 | 9 | 16 | 10 |
| **Mod** | +7 | +0 | +7 | -1 | +3 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Giant, Primordial
**Saving Throws:** Wis +10, Cha +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; paralyzed; petrified; poisoned; prone

---

### Traits

**Awakening of the Scion.** The cradle is a container for the scion of Grolantor. When the cradle drops to 0 hit points, its body crumbles to dirt and moss. The scion instantly appears in the space the cradle occupied and uses the cradle's initiative count.

**Legendary Resistance (5/Day).** If the cradle fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The cradle has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The cradle deals double damage to objects and structures.


---

### Actions

**Multiattack.** The cradle makes three Slam or Spit Rock attacks in any combination and one Grasping Root attack.

**Slam.** Melee Weapon Attack: +14 to hit, reach 20 ft., one target. *Hit:* 33 (4d12 + 7) bludgeoning damage.

**Spit Rock.** Ranged Weapon Attack: +14 to hit, range 120 ft., one target. *Hit:* 25 (4d8 + 7) bludgeoning damage, and the target must succeed on a DC 22 Strength saving throw or have the prone condition.

**Grasping Root.** Melee Weapon Attack: +14 to hit, reach 30 ft., one creature not grappled by the cradle. *Hit:* the target has the grappled condition (escape DC 17). Until the grapple ends, the target takes 29 (4d10 + 7) bludgeoning damage at the start of each of its turns. The root has AC 19 and can be severed by dealing 15 or more slashing damage to it on one attack. Cutting the root doesn't hurt the cradle but ends the grapple.

**Rolling Hills (Recharge 6).** The cradle magically creates a wave of dirt that extends from a point on the ground within 120 feet of itself. The wave is up to 30 feet long, up to 30 feet tall, and up to 30 feet wide. Each creature in the wave must make a DC 22 Strength saving throw. On a failed save, a creature takes 58 (9d12) bludgeoning damage, has the prone condition, and is buried under dirt. On a successful save, a creature takes half as much damage only.
A buried creature has the restrained condition, has 3, and can't breathe. As an action, a creature buried in this way, or another creature within 5 feet of it that isn't buried, can make a DC 17 Strength (Athletics) check. On a successful check, the buried creature no longer has the prone or restrained conditions.


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