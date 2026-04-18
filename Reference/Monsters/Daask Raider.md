---
type: pc
race: "Humanoid (gnoll)"
class:
 - "Daask Raider"
subClass:
 - "CR 1"
cover: "Daask Raider.png"
campaign:
locations:
tags:
  - race/gnoll
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/efa
---
###### Daask Raider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Daask Raider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (gnoll) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 13 | 10 | 11 | 8 |
| **Mod** | +3 | +1 | +1 | +0 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Common, Gnoll
**Saving Throws:** Str +5
**Skills:** Athletics +5, Perception +2

---

### Traits

**Pack Tactics.** The raider has Advantage on an attack roll against a creature if at least one of the raider's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Pummel.** m +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Bludgeoning damage.


---

### Reactions

**Smackback.**  The raider takes damage from a creature within 5 feet.  The raider makes one Pummel attack, targeting the triggering creature.


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