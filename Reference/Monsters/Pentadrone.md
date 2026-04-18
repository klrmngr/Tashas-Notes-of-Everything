---
type: pc
race: "Construct"
class:
 - "Pentadrone"
subClass:
 - "CR 2"
cover: "Pentadrone.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/2
  - source/mm
---
###### Pentadrone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Pentadrone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 32 (5d10 + 5) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 12 | 10 | 10 | 13 |
| **Mod** | +2 | +2 | +1 | +0 | +0 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 14
**Languages:** Modron
**Skills:** Perception +4

---

### Traits

**Axiomatic Mind.** The pentadrone can't be compelled to act in a manner contrary to its nature or its instructions.

**Disintegration.** If the pentadrone dies, its body disintegrates into dust, leaving behind its weapons and anything else it was carrying.


---

### Actions

**Multiattack.** The pentadrone makes five arm attacks.

**Arm.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.

**Paralysis Gas (Recharge 5–6).** The pentadrone exhales a 30-foot cone of gas. Each creature in that area must succeed on a DC 11 Constitution saving throw or be paralyzed for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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