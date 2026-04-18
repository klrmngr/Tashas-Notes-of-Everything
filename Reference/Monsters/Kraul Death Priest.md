---
type: pc
race: "Humanoid (kraul)"
class:
 - "Kraul Death Priest"
subClass:
 - "CR 4"
cover: "Kraul Death Priest.png"
campaign:
locations:
tags:
  - race/kraul
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/ggr
---
###### Kraul Death Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Kraul Death Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (kraul) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid (kraul) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 14 | 12 | 15 | 10 |
| **Mod** | +3 | +1 | +2 | +1 | +2 | +0 |

**Speed:** 30 ft., climb 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Kraul
**Saving Throws:** Con +4, Wis +4
**Skills:** Insight +4, Nature +3, Religion +3

---

### Traits

**Feed on Death.** When a creature within 30 feet of the kraul drops to 0 hit points, the kraul or another creature of its choice within 30 feet of it gains 5 (1d10) temporary hit points, provided the kraul isn't incapacitated.

**Hive Mind.** The kraul is immune to the charmed and frightened conditions while within 30 feet of at least one other kraul.

**Pack Tactics.** The kraul has advantage on an attack roll against a creature if at least one of the kraul's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Spider Climb.** The kraul can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The kraul makes one attack with its quarterstaff and casts one of its spells with a casting time of 1 action.

**Quarterstaff.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage, or 7 (1d8 + 3) bludgeoning damage if used with two hands.


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