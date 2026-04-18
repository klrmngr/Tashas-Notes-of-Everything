---
type: pc
race: "Monstrosity (titan)"
class:
 - "Elder Dinosaur"
subClass:
 - "CR 30"
cover: "Elder Dinosaur.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/30
  - source/psx
---
###### Elder Dinosaur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSX
___

> [!infobox|no-t right]
> ![[Elder Dinosaur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 30 (155,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 25 (natural armor) |
> | :FasHeart: HP | 676 (33d20 + 330) |
> | :FasUserGroup: Race | Monstrosity (titan) |
> | :FasBook: Source | PSX |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 11 | 30 | 3 | 11 | 11 |
| **Mod** | +10 | +0 | +10 | -4 | +0 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Int +5, Wis +9, Cha +9
**Damage Immunities:** fire; poison; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; frightened; paralyzed; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the elder dinosaur fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The elder dinosaur has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The elder dinosaur deals double damage to objects and structures.

**Uniqueness.** These statistics are shared by all six elder dinosaurs: [[Elder Dinosaur (Etali, Primal Storm)|Etali, Primal Storm]], [[Elder Dinosaur (Ghalta, Primal Hunger)|Ghalta, Primal Hunger]], [[Elder Dinosaur (Nezahal, Primal Tide)|Nezahal, Primal Tide]], [[Elder Dinosaur (Tetzimoc, Primal Death)|Tetzimoc, Primal Death]], [[Elder Dinosaur (Zacama, Primal Calamity)|Zacama, Primal Calamity]], [[Elder Dinosaur (Zetalpa, Primal Dawn)|Zetalpa, Primal Dawn]]


---

### Actions

**Frightful Presence.** Each creature of the elder dinosaur's choice within 120 feet of it and aware of it must succeed on a DC 17 Wisdom saving throw or become frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, with disadvantage if the elder dinosaur is within line of sight, ending the effect on itself ona success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the elder dinosaur's Frightful Presence for the next 24 hours.

**Swallow.** The elder dinosaur makes one bite attack against a Large or smaller creature it is grappling. If the attack hits, that creature takes the bite's damage, the target is swallowed, and the grapple ends. While swallowed, the creature is blinded and restrained, it has 3 against attacks and other effects outside the elder dinosaur, and it takes 56 (16d6) acid damage at the start of each of the elder dinosaur's turns. If the elder dinosaur takes 60 damage or more on a single turn from a creature inside it, it must succeed on a DC 20 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 10 feet of it. If the elder dinosaur dies, a swallowed creature is no longer restrained by it and can escape from the corpse by using 20 feet of movement, exiting prone.


---

### Legendary Actions

### 

**Attack.** The elder dinosaur makes one claw attack, tail attack, wing attack, or flipper attack.

**Move.** The elder dinosaur moves up to half its speed.

**Chomp (Costs 2 Actions).** The elder dinosaur makes one bite attack or uses its Swallow.


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