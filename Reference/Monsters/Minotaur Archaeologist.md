---
type: pc
race: "Humanoid"
class:
 - "Minotaur Archaeologist"
subClass:
 - "CR 1/4"
cover: "Minotaur Archaeologist.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/bmt
---
###### Minotaur Archaeologist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Minotaur Archaeologist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 18 (4d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 11 | 13 | 12 | 10 |
| **Mod** | +1 | +0 | +0 | +1 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common
**Skills:** Arcana +3, History +5, Perception +5, Religion +3

---

### Traits

**Labyrinthine Recall.** The minotaur can perfectly recall any path it has traveled.


---

### Actions

**Gore.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage. If the minotaur moved at least 10 feet straight toward the target immediately before it hit, the target takes an extra 3 (1d6) piercing damage, and if the target is a Large or smaller creature, it must succeed on a DC 11 Strength saving throw or be pushed up to 10 feet from the minotaur and have the prone condition.


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