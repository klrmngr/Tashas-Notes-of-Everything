---
type: pc
race: "Dragon"
class:
 - "Adult Bronze Dragon"
subClass:
 - "CR 15"
cover: "Adult Bronze Dragon.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/huge
  - cr/15
  - source/mm
---
###### Adult Bronze Dragon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Adult Bronze Dragon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Dragon |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 212 (17d12 + 102) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 23 | 16 | 15 | 19 |
| **Mod** | +7 | +0 | +6 | +3 | +2 | +4 |

**Speed:** 40 ft., fly 80 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 22
**Languages:** Common, Draconic
**Saving Throws:** Dex +5, Con +11, Wis +7, Cha +9
**Skills:** Insight +7, Perception +12, Stealth +5
**Damage Immunities:** lightning

---

### Traits

**Amphibious.** The dragon can breathe air and water.

**Legendary Resistance (3/Day).** If the dragon fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** The dragon can use its Frightful Presence. It then makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 18 (2d10 + 7) piercing damage.

**Claw.** Melee Weapon Attack: +12 to hit, reach 5 ft., one target. *Hit:* 14 (2d6 + 7) slashing damage.

**Tail.** Melee Weapon Attack: +12 to hit, reach 15 ft., one target. *Hit:* 16 (2d8 + 7) bludgeoning damage.

**Frightful Presence.** Each creature of the dragon's choice that is within 120 feet of the dragon and aware of it must succeed on a DC 17 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the dragon's Frightful Presence for the next 24 hours.

**Breath Weapons (Recharge 5–6).** The dragon uses one of the following breath weapons.
- **Lightning Breath.** The dragon exhales lightning in a 90-foot line that is 5 feet wide. Each creature in that line must make a DC 19 Dexterity saving throw, taking 66 (12d10) lightning damage on a failed save, or half as much damage on a successful one.
- **Repulsion Breath.** The dragon exhales repulsion energy in a 30-foot cone. Each creature in that area must succeed on a DC 19 Strength saving throw. On a failed save, the creature is pushed 60 feet away from the dragon.

**Change Shape.** The dragon magically polymorphs into a humanoid or beast that has a challenge rating no higher than its own, or back into its true form. It reverts to its true form if it dies. Any equipment it is wearing or carrying is absorbed or borne by the new form (the dragon's choice).
In a new form, the dragon retains its alignment, hit points, Hit Dice, ability to speak, proficiencies, Legendary Resistance, lair actions, and Intelligence, Wisdom, and Charisma scores, as well as this action. Its statistics and capabilities are otherwise replaced by those of the new form, except any class features or legendary actions of that form.


---

### Legendary Actions

### 

**Detect.** The dragon makes a Wisdom (Perception) check.

**Tail Attack.** The dragon makes a tail attack.

**Wing Attack (Costs 2 Actions).** The dragon beats its wings. Each creature within 10 feet of the dragon must succeed on a DC 20 Dexterity saving throw or take 14 (2d6 + 7) bludgeoning damage and be knocked prone. The dragon can then fly up to half its flying speed.


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