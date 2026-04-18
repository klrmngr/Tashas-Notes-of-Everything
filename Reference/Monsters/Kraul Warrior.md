---
type: pc
race: "Humanoid (kraul)"
class:
 - "Kraul Warrior"
subClass:
 - "CR 1/2"
cover: "Kraul Warrior.png"
campaign:
locations:
tags:
  - race/kraul
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/ggr
---
###### Kraul Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Kraul Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (kraul) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (kraul) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 13 | 10 | 11 | 8 |
| **Mod** | +2 | +1 | +1 | +0 | +0 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Kraul, understands Common but can't speak it

---

### Traits

**Hive Mind.** The kraul is immune to the charmed and frightened conditions while within 30 feet of at least one other kraul.

**Pack Tactics.** The kraul has advantage on an attack roll against a creature if at least one of the kraul's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Spider Climb.** The kraul can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Spear.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing damage if used with two hands to make a melee attack.


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