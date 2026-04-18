---
type: pc
race: "Humanoid"
class:
 - "Minotaur Infiltrator"
subClass:
 - "CR 2"
cover: "Minotaur Infiltrator.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/bmt
---
###### Minotaur Infiltrator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Minotaur Infiltrator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 14 | 8 | 16 | 10 |
| **Mod** | +4 | +0 | +2 | -1 | +3 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 17
**Languages:** Abyssal, Common
**Skills:** Deception +2, Perception +7, Religion +1

---

### Traits

**Labyrinthine Recall.** The minotaur can perfectly recall any path it has traveled.


---

### Actions

**Gore.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage, or 13 (2d8 + 4) piercing damage while enlarged. If the minotaur moved at least 10 feet straight toward the target immediately before it hit, the target takes an extra 4 (1d8) piercing damage, or 9 (2d8) piercing damage if the minotaur is enlarged. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be pushed up to 10 feet from the minotaur and have the prone condition.

**Mattock.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 10 (1d12 + 4) bludgeoning damage, or 17 (2d12 + 4) bludgeoning damage while enlarged. If the target is a creature and the minotaur is enlarged, the target must succeed on a DC 14 Strength saving throw or have the prone condition.

**Enlarge (Recharges after a Short or Long Rest).** For 1 minute, the minotaur magically increases in size, along with anything it is wearing or carrying. While enlarged, the minotaur is Large, doubles its damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If the minotaur lacks the room to become Large, the minotaur doesn't change size.


---

### Bonus Actions

**Unerring Tracker.** The minotaur magically creates a psychic link with one creature it can see. For the next hour, the minotaur knows the current distance and direction to the target if it is on the same plane of existence. The link ends if the minotaur has the incapacitated condition or uses this ability on a different target.


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