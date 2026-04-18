---
type: pc
race: "Fey"
class:
 - "Valenar Steed"
subClass:
 - "CR 1/2"
cover: "Valenar Steed.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/1-2
  - source/erlw
---
###### Valenar Steed
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Valenar Steed.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (3d10 + 6) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 14 | 10 | 15 | 11 |
| **Mod** | +2 | +3 | +2 | +0 | +2 | +0 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** understands Common, Elvish, and Sylvan but can't speak
**Skills:** Perception +4

---

### Traits

**Bonding.** The steed can magically bond with one creature it can see, immediately after spending at least 1 hour observing that creature while within 30 feet of it. The bond lasts until the steed bonds with a different creature or until the bonded creature dies. While bonded, the steed and the bonded creature can communicate telepathically with each other at a distance of up to 100 feet.


---

### Actions

**Hooves.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage.


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