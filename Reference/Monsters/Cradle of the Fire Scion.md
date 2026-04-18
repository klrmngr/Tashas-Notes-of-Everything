---
type: pc
race: "Elemental"
class:
 - "Cradle of the Fire Scion"
subClass:
 - "CR 25"
cover: "Cradle of the Fire Scion.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/25
  - source/bgg
---
###### Cradle of the Fire Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cradle of the Fire Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 555 (30d20 + 240) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 12 | 27 | 12 | 20 | 17 |
| **Mod** | +9 | +1 | +8 | +1 | +5 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Giant, Primordial
**Damage Resistances:** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; petrified; poisoned

---

### Traits

**Awakening of the Scion.** The cradle is a container for the [[scion of Surtur]]. When the cradle drops to 0 hit points, its body hardens and crumbles to ash. The scion instantly appears in the space the cradle occupied and uses the cradle's initiative count.

**Legendary Resistance (5/Day).** If the cradle fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The cradle has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The cradle deals double damage to objects and structures.


---

### Actions

**Multiattack.** The cradle makes three Slam or Hurl Lava attacks in any combination.

**Slam.** Melee Weapon Attack: +17 to hit, reach 20 ft., one target. *Hit:* 31 (4d10 + 9) bludgeoning damage plus 14 (4d6) fire damage.

**Hurl Lava.** Ranged Weapon Attack: +17 to hit, range 120 ft., one target. *Hit:* 27 (4d8 + 9) fire damage. If the target is a creature or a flammable object, it ignites. Until a creature within 5 feet of the fire takes an action to douse the fire, the target takes 10 (3d6) fire damage at the start of each of its turns.

**Erupting Breath (Recharge 5–6).** The cradle exhales flames and volcanic gases in a 90-foot cone. Each creature in that area must make a DC 24 Dexterity saving throw. On a failed save, a creature takes 55 (10d10) fire damage and has the poisoned condition for 1 minute. On a successful save, a creature takes half as much damage only.
A creature poisoned in this way can make a DC 24 Constitution saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Lava Geyser.** The cradle causes lava to erupt from a point on the ground it can see within 120 feet of itself. Each creature in a 20-foot-radius, 50-foot-high cylinder centered on that point must succeed on a DC 21 Dexterity saving throw or take 14 (4d6) fire damage.


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