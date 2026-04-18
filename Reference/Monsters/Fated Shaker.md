---
type: pc
race: "Humanoid"
class:
 - "Fated Shaker"
subClass:
 - "CR 5"
cover: "Fated Shaker.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/5
  - source/mpp
---
###### Fated Shaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Fated Shaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13; 16 with mage armor |
> | :FasHeart: HP | 76 (17d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 10 | 15 | 16 | 15 |
| **Mod** | +0 | +3 | +0 | +2 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus two more languages
**Saving Throws:** Int +5, Wis +6
**Skills:** Insight +6, Investigation +5, Perception +6

---

### Actions

**Multiattack.** The shaker makes two Golden Rod or Radiant Bolt attacks.

**Golden Rod.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage plus 9 (2d8) radiant damage.

**Radiant Bolt.** Ranged Spell Attack: +6 to hit, range 120 ft., one target. *Hit:* 14 (2d10 + 3) radiant damage.


---

### Bonus Actions

**Commanding Words.** The shaker speaks magical words to order a creature it can see within 30 feet of itself. The target must succeed on a DC 14 Wisdom saving throw or be affected by one of the following effects (choose one or roll a d4):
- **1-2: Grovel.** The target takes 14 (4d6) psychic damage, drops whatever it is holding, and has the prone condition.
- **3-4: Cower.** The target takes 10 (3d6) psychic damage and has the frightened condition until the end of its next turn.


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