---
type: pc
race: "Plant"
class:
 - "Myconid Sprout"
subClass:
 - "CR 0"
cover: "Myconid Sprout.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/0
  - source/mm
---
###### Myconid Sprout
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Myconid Sprout.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 10 | 10 | 8 | 11 | 5 |
| **Mod** | -1 | +0 | +0 | -1 | +0 | -3 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** —

---

### Traits

**Distress Spores.** When the myconid takes damage, all other myconids within 240 feet of it can sense its pain.

**Sun Sickness.** While in sunlight, the myconid has disadvantage on ability checks, attack rolls, and saving throws. The myconid dies if it spends more than 1 hour in direct sunlight.


---

### Actions

**Fist.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 1 (1d4 - 1) bludgeoning damage plus 2 (1d4) poison damage.

**Rapport Spores (3/Day).** A 10-foot radius of spores extends from the myconid. These spores can go around corners and affect only creatures with an Intelligence of 2 or higher that aren't undead, constructs, or elementals. Affected creatures can communicate telepathically with one another while they are within 30 feet of each other. The effect lasts for 1 hour.


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