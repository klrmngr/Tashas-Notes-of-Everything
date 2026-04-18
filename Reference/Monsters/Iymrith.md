---
type: pc
race: "Dragon"
class:
 - "Iymrith"
subClass:
 - "CR 23"
cover: "Iymrith.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/gargantuan
  - cr/23
  - source/skt
---
###### Iymrith
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Iymrith.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 23 (50,000 XP) |
> | :RiSwordFill: Type | Gargantuan Dragon |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 22 (natural armor) |
> | :FasHeart: HP | 481 (26d20 + 208) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 29 | 10 | 27 | 18 | 17 | 21 |
| **Mod** | +9 | +0 | +8 | +4 | +3 | +5 |

**Speed:** 40 ft., burrow 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 120 ft., passive Perception 27
**Languages:** Common, Draconic, Giant, Terran
**Saving Throws:** Dex +7, Con +15, Wis +10, Cha +12
**Skills:** Perception +17, Stealth +7
**Damage Immunities:** lightning

---

### Traits

**Legendary Resistance (3/Day).** If Iymrith fails a saving throw, she can choose to succeed instead.


---

### Actions

**Multiattack.** Iymrith can use her Frightful Presence. She then makes three attacks: one with her bite and two with her claws.

**Bite.** Melee Weapon Attack: +16 to hit, reach 15 ft., one target. *Hit:* 20 (2d10 + 9) piercing damage plus 11 (2d10) lightning damage.

**Claw.** Melee Weapon Attack: +16 to hit, reach 10 ft., one target. *Hit:* 16 (2d6 + 9) slashing damage.

**Tail.** Melee Weapon Attack: +16 to hit, reach 20 ft., one target. *Hit:* 18 (2d8 + 9) bludgeoning damage.

**Frightful Presence.** Each creature of Iymrith's choice that is within 120 feet of Iymrith and aware of it must succeed on a DC 20 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to Iymrith's Frightful Presence for the next 24 hours.

**Lightning Breath (Recharge 5–6).** Iymrith exhales lightning in a 120-foot line that is 10 feet wide. Each creature in that line must make a DC 23 Dexterity saving throw, taking 88 (16d10) lightning damage on a failed save, or half as much damage on a successful one.

**Change Shape.** Iymrith magically polymorphs into a female [[Storm Giant]] or back into her true form. She reverts to her true form if she dies. Any equipment she is wearing or carrying is absorbed or borne by the new form (Iymrith's choice).
In storm giant form, Iymrith retains her alignment, hit points, Hit Dice, ability to speak, proficiencies, Legendary Resistance, lair actions, and Intelligence, Wisdom, and Charisma scores, as well as this action. Her statistics are otherwise replaced by those of the new form.


---

### Legendary Actions

### 

**Detect.** Iymrith makes a Wisdom (Perception) check.

**Tail Attack.** Iymrith makes a tail attack.

**Wing Attack (Costs 2 Actions).** Iymrith beats her wings. Each creature within 15 feet of Iymrith must succeed on a DC 24 Dexterity saving throw or take 16 (2d6 + 9) bludgeoning damage and be knocked prone. Iymrith can then fly up to half her flying speed.


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