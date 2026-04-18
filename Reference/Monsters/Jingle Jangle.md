---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Jingle Jangle"
subClass:
 - "CR 1/4"
cover: "Jingle Jangle.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/wbtw
---
###### Jingle Jangle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Jingle Jangle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 (leather armor, shield) |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 10 | 10 | 8 | 8 |
| **Mod** | -1 | +2 | +0 | +0 | -1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** Common, Goblin
**Skills:** Stealth +6

---

### Traits

**Nimble Escape.** Jingle Jangle can take the Disengage or Hide action as a bonus action on each of her turns.


---

### Actions

**Flail of Locks.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (3d4) bludgeoning damage.


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