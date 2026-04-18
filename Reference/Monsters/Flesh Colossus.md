---
type: pc
race: "Construct"
class:
 - "Flesh Colossus"
subClass:
 - "CR 20"
cover: "Flesh Colossus.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/gargantuan
  - cr/20
  - source/bgg
---
###### Flesh Colossus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Flesh Colossus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 20 (25,000 XP) |
> | :RiSwordFill: Type | Gargantuan Construct |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 280 (16d20 + 112) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 9 | 24 | 6 | 10 | 5 |
| **Mod** | +7 | -1 | +7 | -2 | +0 | -3 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands Giant but can't speak
**Damage Immunities:** lightning; poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Berserk.** If the core inside the colossus is destroyed, the colossus goes berserk. On each of its turns while berserk, the colossus attacks the nearest creature it can see. If no creature is near enough to move to and attack, the colossus attacks an object. Once the colossus goes berserk, it remains berserk until it is destroyed.

**Immutable Form.** The colossus is immune to any spell or effect that would alter its form.

**Magic Resistance.** The colossus has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The colossus deals double damage to objects and structures.


---

### Actions

**Multiattack.** The colossus makes two Fist attacks.

**Fist.** Melee Weapon Attack: +13 to hit (with advantage if the colossus is berserk), reach 20 ft., one target. *Hit:* 17 (3d6 + 7) bludgeoning damage. If the target is a Large or smaller creature, it is pulled up to 15 feet toward the colossus, it has the grappled condition (escape DC 17), and it has the restrained condition until this grapple ends. The colossus can have up to two creatures grappled this way at a time.

**Elemental Breath (Recharge 5–6).** The colossus exhales a cloud swirling with elemental energy in a 90-foot cone. Each creature in that area must make a DC 21 Dexterity saving throw. On a failed save, a creature takes 40 (9d8) damage of a type of the colossus's choosing: acid, cold, fire, or lightning. On a successful save, a creature takes half as much damage.
At the same time as the colossus releases this exhalation, creatures inside the colossus's chest cavity take 40 (9d8) force damage from churning elemental energy.


---

### Bonus Actions

**Bite.** Melee Weapon Attack: +13 to hit, reach 5 ft., one Large or smaller creature grappled by the colossus. *Hit:* 20 (3d8 + 7) bludgeoning damage, and the creature is swallowed. A swallowed creature has the restrained condition, has 3 against attacks and other effects outside the colossus, and takes 10 (3d6) force damage at the start of each of the colossus's turns.
The colossus's chest cavity can hold up to two creatures at a time. Inside its chest cavity is its core, which is a Large object with AC 16 that is immune to lightning, poison, and psychic damage. It has 140 hit points and sheds dim light in a 10-foot radius. If the core is destroyed, the colossus regurgitates all swallowed creatures, each of which falls in a space within 10 feet of the colossus and has the prone condition, and the colossus can no longer swallow a creature. If the colossus dies, any swallowed creature no longer has the restrained condition and can escape from the corpse using 10 feet of movement, exiting with the prone condition.


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