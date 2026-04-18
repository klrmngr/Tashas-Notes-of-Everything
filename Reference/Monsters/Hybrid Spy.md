---
type: pc
race: "Humanoid (simic hybrid)"
class:
 - "Hybrid Spy"
subClass:
 - "CR 1/2"
cover: "Hybrid Spy.png"
campaign:
locations:
tags:
  - race/simic hybrid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/ggr
---
###### Hybrid Spy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Hybrid Spy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (simic hybrid) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (simic hybrid) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 17 | 12 | 13 | 14 | 9 |
| **Mod** | +0 | +3 | +1 | +1 | +2 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common plus any one language
**Skills:** Perception +4, Stealth +5

---

### Traits

**Chameleon Skin.** The hybrid has advantage on Dexterity (Stealth) checks made to hide.

**Spider Climb.** The hybrid can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The hybrid makes two shortsword attacks.

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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