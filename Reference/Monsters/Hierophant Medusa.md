---
type: pc
race: "Monstrosity"
class:
 - "Hierophant Medusa"
subClass:
 - "CR 17"
cover: "Hierophant Medusa.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/17
  - source/bmt
---
###### Hierophant Medusa
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Hierophant Medusa.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 237 (25d10 + 100) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 20 | 18 | 15 | 23 | 22 |
| **Mod** | +6 | +5 | +4 | +2 | +6 | +6 |

**Speed:** 40 ft., climb 40 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 22
**Languages:** Common plus any three languages (Abyssal, Celestial, Druidic, or Infernal recommended)
**Saving Throws:** Con +10, Wis +12
**Skills:** Insight +12, Perception +12, Persuasion +12, Religion +8, Stealth +11
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; petrified; poisoned

---

### Traits

**Devotion's Call (1/Day).** The medusa can cast the Resurrection spell, requiring no material components and using Wisdom as the spellcasting ability.

**Legendary Resistance (4/Day).** If the medusa fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The medusa makes one Constrict attack, one Final Blade attack, and one Snake Hair attack. Alternatively, it makes two Wrathful Strike attacks.

**Constrict.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage, and if the target is a Medium or smaller creature, it has the grappled condition (escape DC 20). Until this grapple ends, the target has the restrained condition, and the medusa can't constrict another creature.

**Final Blade.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage plus 21 (6d6) force damage. If the target has at least one head and the medusa rolled a 20 on the attack roll, the target is decapitated and dies if it fails a DC 20 Constitution saving throw and can't survive without that head. A target is immune to this effect if it takes none of the damage, has legendary actions, or is Huge or larger. Such a creature takes an extra 28 (8d6) force damage from the hit.

**Snake Hair.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 11 (1d10 + 6) piercing damage plus 5 (1d10) poison damage.

**Wrathful Strike.** Ranged Spell Attack: +12 to hit, range 120 ft., one creature. *Hit:* 22 (3d10 + 6) radiant damage, and the target has the blinded condition until the end of its next turn.


---

### Bonus Actions

**Petrifying Gaze (Recharge 4–6).** The medusa unleashes petrifying magic from its eyes in a 30-foot cone. Each creature in that area must make a DC 18 Constitution saving throw if it doesn't have the blinded condition. If the saving throw fails by 5 or more, the creature has the petrified condition. Otherwise, on a failed save, the creature takes 10 (3d6) force damage, begins to turn to stone, and has the restrained condition. The restrained creature must repeat the saving throw at the end of its next turn. On a failed save, it has the petrified condition, and on a successful save, the effect ends on it. The petrification lasts until the creature is freed by the Greater Restoration spell or other magic.
A creature can use its reaction, if available, to shut its eyes to avoid the saving throw. If the creature does so, it has the blinded condition until the end of its next turn.


---

### Legendary Actions

### 

**Move.** The medusa moves up to its speed without provoking opportunity attacks.

**Wrathful Blast (Costs 2 Actions).** The medusa makes one Wrathful Strike attack.

**Final Slash (Costs 3 Actions).** The medusa makes one Final Blade attack with advantage.


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