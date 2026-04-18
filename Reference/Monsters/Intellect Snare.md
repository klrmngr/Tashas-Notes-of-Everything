---
type: pc
race: "Aberration"
class:
 - "Intellect Snare"
subClass:
 - "CR 8"
cover: "Intellect Snare.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/8
  - source/pabtso
---
###### Intellect Snare
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Phandelver and Below: The Shattered Obelisk
___

> [!infobox|no-t right]
> ![[Intellect Snare.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 99 (18d6 + 36) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Phandelver and Below: The Shattered Obelisk |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 15 | 23 | 17 | 11 |
| **Mod** | +1 | +4 | +2 | +6 | +3 | +0 |

**Speed:** 0 ft., fly 45 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (can't see beyond this radius), passive Perception 13
**Languages:** Deep Speech, telepathy 120 ft.
**Saving Throws:** Int +9, Wis +6, Cha +3
**Damage Immunities:** psychic
**Condition Immunities:** blinded; charmed; frightened; prone

---

### Traits

**Cacophony of Minds.** Any creature that starts its turn within 30 feet of the intellect snare must succeed on a DC 17 Wisdom saving throw or have the incapacitated condition for 1 minute. An incapacitated creature can repeat the saving throw at the start of each of its turns, ending the effect on itself on a success. A creature that succeeds on the saving throw is immune to this intellect snare's Cacophony of Minds for 24 hours.

**Magic Resistance.** The intellect snare has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The intellect snare makes two Tentacle attacks.

**Tentacle.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 10 (1d8 + 6) force damage, and if the target is a Medium or smaller creature, the target has the grappled condition (escape DC 17).


---

### Bonus Actions

**Siphon Thoughts.** The intellect snare targets one creature it is grappling. The target must make a DC 17 Intelligence saving throw, taking 21 (6d6) psychic damage on a failed save, or half as much damage on a successful one. The intellect snare then regains a number of hit points equal to the amount of damage taken.


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