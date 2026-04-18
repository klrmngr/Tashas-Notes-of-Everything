---
type: pc
race: "Fey (goblinoid)"
class:
 - "Hobgoblin Warrior"
subClass:
 - "CR 1/2"
cover: "Hobgoblin Warrior.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/1-2
  - source/xmm
---
###### Hobgoblin Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Hobgoblin Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Fey (goblinoid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Fey (goblinoid) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 12 | 12 | 10 | 10 | 9 |
| **Mod** | +1 | +1 | +1 | +0 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common, Goblin

---

### Traits

**Pack Tactics.** The hobgoblin has Advantage on an attack roll against a creature if at least one of the hobgoblin's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Longsword.** m +3, reach 5 ft. *Hit:* 12 (2d10 + 1) Slashing damage.

**Longbow.** r +3, range 150/600 ft. *Hit:* 5 (1d8 + 1) Piercing damage plus 7 (3d4) Poison damage.


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