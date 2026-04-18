---
type: pc
race: "Ooze"
class:
 - "Elder Oblex"
subClass:
 - "CR 10"
cover: "Elder Oblex.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/huge
  - cr/10
  - source/mtf
---
###### Elder Oblex
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Elder Oblex.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Ooze |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 115 (10d12 + 50) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 21 | 22 | 13 | 18 |
| **Mod** | +2 | +3 | +5 | +6 | +1 | +4 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this distance), passive Perception 15
**Languages:** Common plus six more
**Saving Throws:** Int +10, Cha +8
**Skills:** Arcana +10, Deception +8, History +10, Nature +10, Perception +5, Religion +10
**Condition Immunities:** blinded; charmed; deafened; exhaustion; prone

---

### Traits

**Amorphous.** The oblex can move through a space as narrow as 1 inch wide without squeezing.

**Aversion to Fire.** If the oblex takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.

**Sulfurous Impersonation.** As a bonus action, the oblex can extrude a piece of itself that assumes the appearance of one Medium or smaller creature whose memories it has stolen. This simulacrum appears, feels, and sounds exactly like the creature it impersonates, though it smells faintly of sulfur. The oblex can impersonate 2d6 + 1 different creatures, each one tethered to its body by a strand of slime that can extend up to 120 feet away. For all practical purposes, the simulacrum is the oblex, meaning the oblex occupies its space and the simulacrum's space simultaneously. The slimy tether is immune to damage, but it is severed if there is no opening at least 1 inch wide between the oblex's main body and the simulacrum. The simulacrum disappears if the tether is severed.


---

### Actions

**Multiattack.** The elder oblex makes two pseudopod attacks and uses Eat Memories.

**Pseudopod.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 17 (4d6 + 3) bludgeoning damage plus 7 (2d6) psychic damage.

**Eat Memories.** The oblex targets one creature it can see within 5 feet of it. The target must succeed on a DC 18 Wisdom saving throw or take 44 (8d10) psychic damage and become memory drained until it finishes a short or long rest or until it benefits from the greater restoration or heal spell. Constructs, oozes, plants, and undead succeed on the save automatically.
While memory drained, the target must roll a d4 and subtract the number rolled from any ability check or attack roll it makes. Each time the target is memory drained beyond the first, the die size increases by one: the d4 becomes a d6, the d6 becomes a d8, and so on until the die becomes a d20, at which point the target becomes unconscious for 1 hour. The effect then ends.
When an oblex causes a target to become memory drained, the oblex learns all the languages the target knows and gains all its proficiencies, except any saving throw proficiencies.


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