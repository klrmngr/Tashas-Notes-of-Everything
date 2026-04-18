---
type: pc
race: "Beast"
class:
 - "Mountain Goat"
subClass:
 - "CR 1/8"
cover: "Mountain Goat.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1-8
  - source/idrotf
---
###### Mountain Goat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Mountain Goat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Beast |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 14 | 2 | 10 | 5 |
| **Mod** | +2 | +1 | +2 | -4 | +0 | -3 |

**Speed:** 40 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —

---

### Traits

**Charge.** If the goat moves at least 20 feet straight toward a target and then hits it with a ram attack on the same turn, the target takes an extra 3 (1d6) bludgeoning damage. If the target is a creature, it must succeed on a DC 12 Strength saving throw or be knocked prone.

**Sure-Footed.** The goat has advantage on Strength and Dexterity saving throws made against effects that would knock it prone.


---

### Actions

**Ram.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.


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