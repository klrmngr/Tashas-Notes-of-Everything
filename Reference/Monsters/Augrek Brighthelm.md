---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Augrek Brighthelm"
subClass:
 - "CR —"
cover: "Augrek Brighthelm.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/skt
---
###### Augrek Brighthelm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Augrek Brighthelm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 15 (chain shirt, shield) |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 15 | 10 | 11 | 11 |
| **Mod** | +2 | +0 | +2 | +0 | +0 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Dwarvish
**Skills:** Athletics +4, Perception +2
**Damage Resistances:** poison

---

### Traits

**Dwarven Resilience.** Augrek has advantage on saving throws against poison.

**Roleplaying Information.** Sheriff's deputy Augrek guards the southwest gate of Bryn Shander and welcomes visitors to town. She has a good heart.
Ideal: "You'll get farther in life with a kind word than an axe."
Bond: "Bryn Shander is my home. It's my job to protect her."
Flaw: "I'm head over heels in love with Sheriff Southwell. One day I hope to marry him."


---

### Actions

**Warhammer.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage, or 7 (1d10 + 2) bludgeoning damage if used with two hands.

**Heavy Crossbow.** Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. *Hit:* 5 (1d10) piercing damage. Augrek carries ten crossbow bolts.


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