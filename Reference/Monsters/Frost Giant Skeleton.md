---
type: pc
race: "Undead"
class:
 - "Frost Giant Skeleton"
subClass:
 - "CR 6"
cover: "Frost Giant Skeleton.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/6
  - source/idrotf
---
###### Frost Giant Skeleton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Frost Giant Skeleton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (armor scraps) |
> | :FasHeart: HP | 102 (12d12 + 24) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 9 | 15 | 6 | 8 | 5 |
| **Mod** | +6 | -1 | +2 | -2 | -1 | -3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** understands Giant but can't speak
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** cold; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Unusual Nature.** The skeleton doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The skeleton makes two greataxe attacks.

**Greataxe.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 25 (3d12 + 6) slashing damage.

**Freezing Stare.** The skeleton targets one creature it can see within 60 feet of it. The target must succeed on a DC 13 Constitution saving throw or take 35 (10d6) cold damage and be paralyzed until the end of its next turn.


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