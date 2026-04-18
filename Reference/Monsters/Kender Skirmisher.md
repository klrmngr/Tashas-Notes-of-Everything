---
type: pc
race: "Humanoid"
class:
 - "Kender Skirmisher"
subClass:
 - "CR 1/4"
cover: "Kender Skirmisher.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-4
  - source/dsotdq
---
###### Kender Skirmisher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Kender Skirmisher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 14 (4d6) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 10 | 12 | 8 | 14 |
| **Mod** | -1 | +3 | +0 | +1 | -1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Kenderspeak
**Skills:** Perception +3, Sleight Of Hand +7, Stealth +5
**Condition Immunities:** frightened

---

### Actions

**Hoopak.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 40/160 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 5 (1d4 + 3) bludgeoning damage if the kender used the hoopak's sling to make a ranged attack.

**Taunt.** The kender launches a barrage of insults at a creature it can see within 60 feet of itself. If the target can hear the kender, the target must succeed on a DC 12 Wisdom saving throw or have disadvantage on attack rolls until the end of its next turn.


---

### Bonus Actions

**Elusive.** The kender takes the Disengage or Hide action.


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