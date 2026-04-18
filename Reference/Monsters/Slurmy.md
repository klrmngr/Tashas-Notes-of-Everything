---
type: pc
race: "Humanoid (goblinoid)"
class:
 - "Slurmy"
subClass:
 - "CR 1/8"
cover: "Slurmy.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-8
  - source/nrh-tcmc
---
###### Slurmy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NRH-TCMC
___

> [!infobox|no-t right]
> ![[Slurmy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Humanoid (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (goblinoid) |
> | :FasBook: Source | NRH-TCMC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 14 | 12 | 8 | 14 | 8 |
| **Mod** | -1 | +2 | +1 | -1 | +2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Skills:** Perception +4

---

### Traits

**Nimble Escape.** Slurmy can take the Disengage or Hide action as a bonus action on each of their turns.


---

### Actions

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.


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