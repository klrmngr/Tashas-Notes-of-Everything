---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Goblin Gang Member"
subClass:
 - "CR 1/4"
cover: "Goblin Gang Member.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/kkw
---
###### Goblin Gang Member
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: KKW
___

> [!infobox|no-t right]
> ![[Goblin Gang Member.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 10 (3d6) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | KKW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 10 | 10 | 10 | 8 |
| **Mod** | -1 | +3 | +0 | +0 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Goblin
**Skills:** Stealth +5

---

### Traits

**Nimble Escape.** The goblin can take the Disengage or Hide action as a bonus action on each of its turns.


---

### Actions

**Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Light Crossbow.** Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.


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