---
type: pc
race: "Construct"
class:
 - "Animated Chained Library"
subClass:
 - "CR 1"
cover: "Animated Chained Library.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/1
  - source/cm
---
###### Animated Chained Library
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Animated Chained Library.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 8 | 14 | 1 | 5 | 1 |
| **Mod** | +2 | -1 | +2 | -5 | -3 | -5 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 7
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned; prone

---

### Traits

**False Object.** If the library is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the library move or act, that creature must succeed on a DC 15 Wisdom (Perception) check to discern that the library is animate.


---

### Actions

**Multiattack.** The library makes two attacks.

**Chained Book.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage, and if the target is a creature, it is grappled (escape DC 12).


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