---
type: pc
race: "Humanoid (any race)"
class:
 - "Scorchbringer Guard"
subClass:
 - "CR 1/2"
cover: "Scorchbringer Guard.png"
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
###### Scorchbringer Guard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Scorchbringer Guard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 14 | 12 | 10 | 9 | 10 |
| **Mod** | +1 | +2 | +1 | +0 | -1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** any one language (usually Common)

---

### Traits

**Explosive Tank.** When the guard dies, or if it rolls a 1 when checking whether its Scorchbringer action recharges, the tank on its back explodes in a 10-foot radius sphere. Each creature in that area must make a DC 12 Dexterity saving throw, taking 7 (2d6) fire damage on a failed save, or half as much damage on a successful one. The explosion ignites flammable objects that aren't being worn or carried, and it destroys the scorchbringer.


---

### Actions

**Light Hammer.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.

**Scorchbringer (Recharge 4–6).** The guard's scorchbringer spouts a stream of flame in a line that is 30 feet long and 5 feet wide. Each creature in the line must make a DC 12 Dexterity saving throw, taking 7 (2d6) fire damage on a failed save, or half as much damage on a successful one.


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