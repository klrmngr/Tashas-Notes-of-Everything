---
type: pc
race: "Fey"
class:
 - "Valenar Hawk"
subClass:
 - "CR 1/8"
cover: "Valenar Hawk.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1-8
  - source/erlw
---
###### Valenar Hawk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Valenar Hawk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 10 (4d4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 18 | 10 | 9 | 16 | 11 |
| **Mod** | -1 | +4 | +0 | -1 | +3 | +0 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** understands Common, Elvish, and Sylvan but can't speak
**Skills:** Perception +5

---

### Traits

**Bonding.** The hawk can magically bond with one creature it can see, immediately after spending at least 1 hour observing that creature while within 30 feet of it. The bond lasts until the hawk bonds with a different creature or until the bonded creature dies. While bonded, the hawk and the bonded creature can communicate telepathically with each other at a distance of up to 100 feet.

**Keen Sight.** The hawk has advantage on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Talons.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) slashing damage.


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