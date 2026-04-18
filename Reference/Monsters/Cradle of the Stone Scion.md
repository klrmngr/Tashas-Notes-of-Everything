---
type: pc
race: "Elemental"
class:
 - "Cradle of the Stone Scion"
subClass:
 - "CR 23"
cover: "Cradle of the Stone Scion.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/23
  - source/bgg
---
###### Cradle of the Stone Scion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cradle of the Stone Scion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 455 (26d20 + 182) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 26 | 15 | 24 | 11 | 18 | 10 |
| **Mod** | +8 | +2 | +7 | +0 | +4 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** tremorsense 120 ft., passive Perception 14
**Languages:** Giant, Primordial
**Saving Throws:** Wis +11, Cha +7
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned; prone

---

### Traits

**Awakening of the Scion.** The cradle is a container for the [[scion of Skoraeus]]. When the cradle drops to 0 hit points, its body crumbles to dust. The scion instantly appears in the space the cradle occupied and uses the cradle's initiative count.

**Legendary Resistance (5/Day).** If the cradle fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The cradle has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The cradle deals double damage to objects and structures.


---

### Actions

**Multiattack.** The cradle makes two Slam or Spit Rock attacks.

**Slam.** Melee Weapon Attack: +15 to hit, reach 20 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage.

**Spit Rock.** Ranged Weapon Attack: +15 to hit, range 120 ft., one target. *Hit:* 24 (3d10 + 8) bludgeoning damage, and the target must succeed on a DC 23 Strength saving throw or have the prone condition.

**Shattering Roar (Recharge 5–6).** The cradle lets out a painfully load roar. Each creature within 60 feet of the cradle must make a DC 23 Constitution saving throw. On a failed save, a creature takes 33 (6d10) thunder damage and has the incapacitated condition until the end of its next turn.


---

### Bonus Actions

**Crystal Flare.** The cradle causes the crystals on its body to flare with light. Each creature within 30 feet of the cradle must succeed on a DC 22 Constitution saving throw or take 21 (6d6) radiant damage and have the blinded condition until the end of the cradle's next turn.

**Stone Spikes.** The cradle causes the ground in a 20-foot square within 90 feet of itself to sprout crystal spikes until the start of its next turn. The area becomes difficult terrain for the duration. A creature takes 10 (3d6) piercing damage for each 5 feet it moves on this terrain.


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