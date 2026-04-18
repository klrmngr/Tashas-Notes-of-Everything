---
type: pc
race: "Humanoid (kobold)"
class:
 - "Kobold Inventor"
subClass:
 - "CR 1/4"
cover: "Kobold Inventor.png"
campaign:
locations:
tags:
  - race/kobold
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/vgm
---
###### Kobold Inventor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Kobold Inventor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (kobold) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Humanoid (kobold) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 15 | 12 | 8 | 7 | 8 |
| **Mod** | -2 | +2 | +1 | -1 | -2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic
**Skills:** Perception +0

---

### Traits

**Sunlight Sensitivity.** While in sunlight, the kobold has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Pack Tactics.** The kobold has advantage on an attack roll against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Sling.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.

**Weapon Invention.** The kobold uses one of the following options (roll a d8 or choose one); the kobold can use each one no more than once per day:
- The kobold hurls a flask of acid. Ranged Weapon Attack: +4 to hit, range 5/20 ft., one target. *Hit:* 7 (2d6) acid damage.
- The kobold throws a flask of alchemist's fire. Ranged Weapon Attack: +4 to hit, range 5/20 ft., one target. *Hit:* 2 (1d4) fire damage at the start of each of the target's turns. A creature can end this damage by using its action to make a DC 10 Dexterity check to extinguish the flames.
- The kobold throws a small basket into a 5-foot-square space within 20 feet of it. A [[Swarm Of Centipedes|swarm of insects (centipedes)]] with 11 hit points emerges from the basket and rolls initiative. At the end of each of the swarm's turns, there's a 50 chance that the swarm disperses.
- The kobold throws a clay pot full of green slime at the target, and it breaks open on impact. Ranged Weapon Attack: +4 to hit, range 5/20 ft., one target. *Hit:* The target is covered in a patch of green slime (see chapter 5 of the Dungeon Master's Guide). Miss: A patch of green slime covers a randomly determined 5-foot-square section of wall or floor within 5 feet of the target.
- The kobold throws a clay pot into a 5-foot-square space within 20 feet of it, and it breaks open on impact. A [[Swarm Of Rot Grubs]] (see appendix A) emerges from the shattered pot and remains a hazard in that square.
- The kobold makes a melee attack with a scorpion tied to the end of a 5-foot-long pole. Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage, and the target must make a DC 9 Constitution saving throw, taking 4 (1d8) poison damage on a failed save, or half as much damage on a successful one.
- The kobold releases a skunk into an unoccupied space within 5 feet of it. The skunk has a walking speed of 20 feet, AC 10, 1 hit point, and no effective attacks. It rolls initiative and, on its turn, uses its action to spray musk at a random creature within 5 feet of it. The target must make a DC 9 Constitution saving throw. On a failed save, the target retches and can't take actions for 1 minute. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. A creature that doesn't need to breathe or is immune to poison automatically succeeds on the saving throw. Once the skunk has sprayed its musk, it can't do so again until it finishes a short or long rest.
- The kobold throws a small bag into a 5-foot-square space within 20 feet of it. A [[Swarm Of Wasps|swarm of insects (wasps)]] with 11 hit points emerges from the bag and rolls initiative. At the end of each of the swarm's turns, there's a 50 chance that the swarm disperses.


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