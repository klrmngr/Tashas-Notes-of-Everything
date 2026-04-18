---
type: pc
race: "Dragon"
class:
 - "Faerie Dragon (Green)"
subClass:
 - "CR 2"
cover: "Faerie Dragon (Green).png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/tiny
  - cr/2
  - source/mm
---
###### Faerie Dragon (Green)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Faerie Dragon (Green).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Tiny Dragon |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 14 (4d4 + 4) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 20 | 13 | 14 | 12 | 16 |
| **Mod** | -4 | +5 | +1 | +2 | +1 | +3 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Draconic, Sylvan
**Skills:** Arcana +4, Perception +3, Stealth +7

---

### Traits

**The Colors of Age.** A faerie dragon's scales change hue as it ages, moving through all the colors of the rainbow. All faerie dragons have innate spellcasting ability, gaining new spells as they mature.
Red—5 years or less
Orange—6–10 years
Yellow—11–20 years
Green—21–30 years
Blue—31–40 years
Indigo—41–50 years
Violet—51 years or more
A green or older faerie dragon's CR increases to 2.

**Superior Invisibility.** As a bonus action, the dragon can magically turn invisible until its concentration ends (as if concentrating on a spell). Any equipment the dragon wears or carries is invisible with it.

**Limited Telepathy.** Using telepathy, the dragon can magically communicate with any other faerie dragon within 60 feet of it.

**Magic Resistance.** The faerie dragon has advantage on saving throws against spells and other magical effects.


---

### Actions

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 1 piercing damage.

**Euphoria Breath (Recharge 5–6).** The dragon exhales a puff of euphoria gas at one creature within 5 feet of it. The target must succeed on a DC 11 Wisdom saving throw, or for 1 minute, the target can't take reactions and must roll a d6 at the start of each of its turns to determine its behavior during the turn:
1–4. The target takes no action or bonus action and uses all of its movement to move in a random direction.
5–6. The target doesn't move, and the only thing it can do on its turn is make a DC 11 Wisdom saving throw, ending the effect on itself on a success.


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