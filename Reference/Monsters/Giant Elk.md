---
type: pc
race: "Beast"
class:
 - "Giant Elk"
subClass:
 - "CR 2"
cover: "Giant Elk.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/2
  - source/mm
---
###### Giant Elk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Giant Elk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 42 (5d12 + 10) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 14 | 7 | 14 | 10 |
| **Mod** | +4 | +3 | +2 | -2 | +2 | +0 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Giant Elk, understands Common, Elvish, Sylvan but can't speak them
**Skills:** Perception +4

---

### Traits

**Charge.** If the elk moves at least 20 feet straight toward a target and then hits it with a ram attack on the same turn, the target takes an extra 7 (2d6) damage. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be knocked prone.


---

### Actions

**Ram.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Hooves.** Melee Weapon Attack: +6 to hit, reach 5 ft., one prone creature. *Hit:* 22 (4d8 + 4) bludgeoning damage.


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