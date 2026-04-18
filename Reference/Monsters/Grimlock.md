---
type: pc
race: "Humanoid (grimlock)"
class:
 - "Grimlock"
subClass:
 - "CR 1/4"
cover: "Grimlock.png"
campaign:
locations:
tags:
  - race/grimlock
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/mm
---
###### Grimlock
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Grimlock.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (grimlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (grimlock) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 12 | 9 | 8 | 6 |
| **Mod** | +3 | +1 | +1 | -1 | -1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. or 10 ft. while deafened (blind beyond this radius), passive Perception 13
**Languages:** Undercommon
**Skills:** Athletics +5, Perception +3, Stealth +3
**Condition Immunities:** blinded

---

### Traits

**Blind Senses.** The grimlock can't use its blindsight while deafened and unable to smell.

**Keen Hearing and Smell.** The grimlock has advantage on Wisdom (Perception) checks that rely on hearing or smell.

**Stone Camouflage.** The grimlock has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.


---

### Actions

**Spiked Bone Club.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage plus 2 (1d4) piercing damage.


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