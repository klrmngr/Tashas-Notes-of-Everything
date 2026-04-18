---
type: pc
race: "Humanoid (any race)"
class:
 - "Anarch"
subClass:
 - "CR 1/4"
cover: "Anarch.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/ggr
---
###### Anarch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Anarch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 13 | 12 | 9 | 11 | 10 |
| **Mod** | +2 | +1 | +1 | -1 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** any one language (usually Common)
**Skills:** Perception +2, Survival +2

---

### Traits

**Aggressive.** As a bonus action, the anarch can move up to its speed toward a hostile creature it can see.

**Siege Monster.** The anarch deals double damage to objects and structures.


---

### Actions

**Spiked Club.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage, or 7 (1d10 + 2) piercing damage if used with two hands.


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