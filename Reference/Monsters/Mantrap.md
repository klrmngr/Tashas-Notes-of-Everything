---
type: pc
race: "Plant"
class:
 - "Mantrap"
subClass:
 - "CR 1"
cover: "Mantrap.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/1
  - source/toa
---
###### Mantrap
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Mantrap.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 45 (7d10 + 7) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 12 | 1 | 10 | 2 |
| **Mod** | +2 | +2 | +1 | -5 | +0 | -4 |

**Speed:** 5 ft. &nbsp;|&nbsp; **Senses:** tremorsense 30 ft., passive Perception 10
**Languages:** —
**Condition Immunities:** blinded; deafened; exhaustion; prone

---

### Traits

**Attractive Pollen (1/Day).** When the mantrap detects any creatures nearby, it can use its reaction to release pollen out to a radius of 30 feet. Any beast or humanoid within the area must succeed on a DC 11 Wisdom saving throw or be forced to use all its movement on its turns to get as close to the the mantrap as possible. An affected target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

**False Appearance.** While the mantrap remains motionless, it is indistinguishable from an ordinary tropical plant.


---

### Actions

**Engulf.** Melee Weapon Attack: +4 to hit, reach 5 ft., one Medium or smaller creature. *Hit:* The target is trapped inside the mantrap's leafy jaws. While trapped in this way, the target is blinded and restrained, has 3 from an attacks and other effects outside the mantrap, and takes 14 (4d6) acid damage at the start of each of the target's turns. If the mantrap dies, the creature inside it is no longer restrained by it. A mantrap can engulf only one creature at a time.


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