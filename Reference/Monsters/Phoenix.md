---
type: pc
race: "Elemental"
class:
 - "Phoenix"
subClass:
 - "CR 16"
cover: "Phoenix.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/gargantuan
  - cr/16
  - source/mpmm
---
###### Phoenix
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Phoenix.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 16 (15,000 XP) |
> | :RiSwordFill: Type | Gargantuan Elemental |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 175 (10d20 + 70) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 26 | 25 | 2 | 21 | 18 |
| **Mod** | +4 | +8 | +7 | -4 | +5 | +4 |

**Speed:** 20 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** —
**Saving Throws:** Wis +10, Cha +9
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire; poison
**Condition Immunities:** exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Fiery Death and Rebirth.** If the phoenix dies, it explodes. Each creature in 60-foot-radius sphere centered on the phoenix must make a DC 20 Dexterity saving throw, taking 22 (4d10) fire damage on a failed save, or half as much damage on a successful one. The fire ignites flammable objects in the area that aren't being worn or carried.
The explosion destroys the phoenix's body and leaves behind an egg-shaped cinder, which weighs 5 pounds. The cinder deals 21 (6d6) fire damage to any creature that touches it, though no more than once per round. The cinder is immune to all damage, and after 1d6 days, it hatches a new phoenix.

**Fire Form.** The phoenix can move through a space as narrow as 1 inch wide without squeezing.
Any creature that touches the phoenix or hits it with a melee attack while within 5 feet of it takes 5 (1d10) fire damage. In addition, the phoenix can enter a hostile creature's space and stop there. The first time it enters a creature's space on a turn, that creature takes 5 (1d10) fire damage.
With a touch, the phoenix can also ignite flammable objects that aren't worn or carried (no action required).

**Flyby.** The phoenix doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Illumination.** The phoenix sheds bright light in a 60-foot radius and dim light for an additional 30 feet.

**Legendary Resistance (3/Day).** If the phoenix fails a saving throw, it can choose to succeed instead.

**Siege Monster.** The phoenix deals double damage to objects and structures.


---

### Actions

**Multiattack.** The phoenix makes two attacks: one Beak attack and one Fiery Talons attack.

**Beak.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 15 (2d6 + 8) fire damage.

**Fiery Talons.** Melee Weapon Attack: +13 to hit, reach 15 ft., one target. *Hit:* 17 (2d8 + 8) fire damage.


---

### Legendary Actions

### 

**Move.** The phoenix moves up to its speed.

**Peck.** The phoenix makes one beak attack.

**Swoop (Costs 2 Actions).** The phoenix moves up to its speed and makes one Fiery Talons attack.


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