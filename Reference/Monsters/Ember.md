---
type: pc
race: "Dragon (adult chromatic)"
class:
 - "Ember"
subClass:
 - "CR 22"
cover: "Ember.png"
campaign:
locations:
tags:
  - race/adult chromatic
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/22
  - source/mcv2dc
---
###### Ember
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Ember.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 22 (41,000 XP) |
> | :RiSwordFill: Type | Huge Dragon (adult chromatic) |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 20 (special equipment) |
> | :FasHeart: HP | 270 (20d12 + 140) |
> | :FasUserGroup: Race | Dragon (adult chromatic) |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 10 | 25 | 17 | 14 | 22 |
| **Mod** | +9 | +0 | +7 | +3 | +2 | +6 |

**Speed:** 40 ft., climb 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 26
**Languages:** Abyssal, Common, Draconic
**Saving Throws:** Dex +7, Con +14, Wis +9, Cha +13
**Skills:** Perception +16, Religion +10, Stealth +14
**Damage Immunities:** fire

---

### Traits

**Calescent Aura.** At the start of Ember's turn, Ember can force any number of creatures of his choice within 10 feet of himself to make a DC 22 Constitution saving throw. On a failed save, a creature takes 7 (2d6) fire damage and is frightened of Ember until the start of its next turn.

**Legendary Resistance (5/Day).** If Ember fails a saving throw, he can choose to succeed instead.

**Special Equipment.** In battle, Ember dons magical plate armor custom-forged for his use. While wearing the armor, Ember adds his Charisma modifier to his weapon damage rolls (included in the attack descriptions), and his AC can't be lower than 20.


---

### Actions

**Multiattack.** Ember makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 26 (2d10 + 15) piercing damage plus 13 (2d6 + 6) fire damage.

**Claw.** Melee Weapon Attack: +16 to hit, reach 5 ft., one target. *Hit:* 22 (2d6 + 15) slashing damage.

**Firestorm Breath (Recharge 5–6).** Ember exhales roiling flames and ash in a 90-foot cone. Each creature in that area must make a DC 22 Dexterity saving throw. On a failed save, a creature takes 56 (16d6) fire damage and is pushed up to 30 feet away from Ember and knocked prone. On a successful save, a creature takes half as much damage with no other effects. If a creature is reduced to 0 hit points by this effect, the creature immediately dies, and its body is reduced to ash.


---

### Bonus Actions

**Alter Shape.** Ember magically transforms into a vulture or a mage and retains his alignment, damage immunities, hit points, and Hit Dice, as well as his Intelligence, Wisdom, and Charisma scores. This transformation ends if Ember is reduced to 0 hit points or if he uses another bonus action to end it.


---

### Legendary Actions

### 

**Pursuit.** Ember moves up to 40 feet in a straight line toward one creature he can see. This movement ignores opportunity attacks.

**Searing Bite (Costs 2 Actions).** Ember makes one Bite attack. If the attack hits, it deals an additional 7 (2d6) fire damage.


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