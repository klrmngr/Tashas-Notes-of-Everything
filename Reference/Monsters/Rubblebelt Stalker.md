---
type: pc
race: "Humanoid (any race)"
class:
 - "Rubblebelt Stalker"
subClass:
 - "CR 1/2"
cover: "Rubblebelt Stalker.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/ggr
---
###### Rubblebelt Stalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Rubblebelt Stalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (piecemeal armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 12 | 10 | 14 | 8 |
| **Mod** | +0 | +2 | +1 | +0 | +2 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** any one language (usually Common)
**Skills:** Athletics +2, Perception +4, Stealth +4

---

### Traits

**Ambusher.** In the first round of a combat, the stalker has advantage on attack rolls against any creature that hasn't taken a turn yet.

**Nimble Escape.** The stalker can take the Disengage or Hide action as a bonus action on each of its turns.

**Ruin Dweller.** The stalker has advantage on Dexterity (Stealth) checks made to hide in ruins, and its speed is not reduced in 3 composed of rubble.

**Siege Monster.** The stalker deals double damage to objects and structures.


---

### Actions

**Multiattack.** The stalker makes three attacks with its shortsword.

**Shortsword.** m attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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