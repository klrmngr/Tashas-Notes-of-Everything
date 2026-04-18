---
type: pc
race: "Aberration"
class:
 - "Otherworldly Corrupter"
subClass:
 - "CR 17"
cover: "Otherworldly Corrupter.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/17
  - source/bmt
---
###### Otherworldly Corrupter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Otherworldly Corrupter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 17 (18,000 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 217 (29d8 + 87) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 22 | 16 | 22 | 18 | 20 |
| **Mod** | +1 | +6 | +3 | +6 | +4 | +5 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 20
**Languages:** Common, telepathy 120 ft., Thieves' cant
**Saving Throws:** Dex +12, Int +12
**Skills:** Perception +10, Stealth +18
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Alien Mind.** Magic and other features can't determine the corrupter's creature type. If a creature tries to read the corrupter's thoughts, that creature must succeed on a DC 20 Intelligence saving throw or have the stunned condition for 1 minute. The stunned creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**Legendary Resistance (3/Day).** If the corrupter fails a saving throw, it can choose to succeed instead.

**Spider Climb.** The corrupter can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The corrupter makes three Whispering Blade attacks and can use Debilitating Touch.

**Whispering Blade.** Melee or Ranged Weapon Attack: +12 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 10 (1d8 + 6) piercing damage plus 14 (4d6) psychic damage. If the target is a creature, it must succeed on a DC 20 Wisdom saving throw or be unable to speak until the start of the corrupter's next turn.

**Debilitating Touch.** The corrupter's squirming tentacle lashes out at a creature the corrupter can see within 30 feet of itself. The target must succeed on a DC 20 Constitution saving throw or have the paralyzed condition until the end of its next turn, after which the target is immune to this Debilitating Touch for 24 hours.


---

### Bonus Actions

**Change Shape.** The corrupter magically transforms into any creature that is Small or Medium, while retaining its game statistics (other than its size). This transformation ends if the corrupter is reduced to 0 hit points or uses a bonus action to end it.


---

### Reactions

**Uncanny Dodge.** When an attacker the corrupter can see hits the corrupter with an attack, the corrupter halves the attack's damage against it.


---

### Legendary Actions

### 

**Cunning.** The corrupter escapes nonmagical restraints and ends the grappled and restrained conditions on itself, then moves up to its speed without provoking opportunity attacks.

**Stab (Costs 2 Actions).** The corrupter makes one Whispering Blade attack.

**Amorphous Escape (Costs 3 Actions).** The corrupter dissolves into a shifting mass of flesh, tentacles, eyes, claws, and mouths. Up to two creatures the corrupter can see within 20 feet of itself must make a DC 20 Intelligence saving throw, taking 18 (4d8) psychic damage on a failed save, or half as much damage on a successful one. This transformation lasts until the end of the corrupter's next turn. While transformed, the corrupter has advantage on attack rolls, attack rolls made against it have disadvantage, and it can move through spaces at least 1 inch wide without squeezing.


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