---
type: pc
race: "Humanoid (any race)"
class:
 - "Druid of the Old Ways"
subClass:
 - "CR 7"
cover: "Druid of the Old Ways.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/ggr
---
###### Druid of the Old Ways
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Druid of the Old Ways.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 16 | 10 | 20 | 14 |
| **Mod** | +0 | +2 | +3 | +0 | +5 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common, Druidic
**Saving Throws:** Dex +5, Con +6, Wis +8
**Skills:** Nature +3, Perception +8, Survival +8

---

### Traits

**Siege Monster.** The druid deals double damage to objects and structures.

**Speak with Beasts and Plants.** The druid can communicate with beasts and plants as if they shared a language.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands.


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