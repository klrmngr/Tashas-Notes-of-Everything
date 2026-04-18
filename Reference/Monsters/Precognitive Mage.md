---
type: pc
race: "Humanoid (any race)"
class:
 - "Precognitive Mage"
subClass:
 - "CR 3"
cover: "Precognitive Mage.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/ggr
---
###### Precognitive Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Precognitive Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 11; 14 with mage armor |
> | :FasHeart: HP | 63 (14d8) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 13 | 10 | 18 | 13 | 11 |
| **Mod** | -1 | +1 | +0 | +4 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 13
**Languages:** Common plus any one language
**Saving Throws:** Int +6, Wis +3
**Skills:** Perception +3

---

### Actions

**Quarterstaff.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two hands.

**Glimpse the Temporal Flood (Recharge 5–6).** The mage targets one creature within 120 feet of it that it can see. The target takes 18 (4d8) psychic damage, and it must succeed on a DC 14 Intelligence saving throw or be stunned until the end of its next turn.


---

### Reactions

**Precognitive Insight (3/Day).** When the mage or a creature it can see makes an attack roll, a saving throw, or an ability check, the mage can cause the roll to be made with advantage or disadvantage.


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