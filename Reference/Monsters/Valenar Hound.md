---
type: pc
race: "Fey"
class:
 - "Valenar Hound"
subClass:
 - "CR 1/2"
cover: "Valenar Hound.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/1-2
  - source/erlw
---
###### Valenar Hound
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Valenar Hound.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 14 | 10 | 15 | 11 |
| **Mod** | +3 | +2 | +2 | +0 | +2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** understands Common, Elvish, and Sylvan but can't speak
**Skills:** Perception +4

---

### Traits

**Bonding.** The hound can magically bond with one creature it can see, immediately after spending at least 1 hour observing that creature while within 30 feet of it. The bond lasts until the hound bonds with a different creature or until the bonded creature dies. While bonded, the hound and the bonded creature can communicate telepathically with each other at a distance of up to 100 feet.

**Keen Hearing and Smell.** The hound has advantage on Wisdom (Perception) checks that rely on hearing or smell.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage. If the target is a creature, it must succeed on a DC 13 Strength saving throw or be knocked prone.


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