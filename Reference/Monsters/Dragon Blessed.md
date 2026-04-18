---
type: pc
race: "Humanoid"
class:
 - "Dragon Blessed"
subClass:
 - "CR 5"
cover: "Dragon Blessed.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/ftd
---
###### Dragon Blessed
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragon Blessed.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (scale mail) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 16 | 14 | 17 | 10 |
| **Mod** | +1 | +0 | +3 | +2 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Draconic, and any two languages
**Saving Throws:** Con +6, Wis +6
**Skills:** Medicine +6, Religion +5
**Condition Immunities:** frightened

---

### Actions

**Multiattack.** The blessed makes two Mace or Radiant Bolt attacks.

**Mace.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) bludgeoning damage plus 18 (4d8) radiant damage.

**Radiant Bolt.** Ranged Spell Attack: +6 to hit, range 120 ft., one target. *Hit:* 22 (5d8) radiant damage, and the blessed regains 5 (1d10) hit points.


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