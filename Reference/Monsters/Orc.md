---
type: pc
race: "Humanoid (orc)"
class:
 - "Orc"
subClass:
 - "CR 1/2"
cover: "Orc.png"
campaign:
locations:
tags:
  - race/orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/mm
---
###### Orc
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Orc.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 15 (2d8 + 6) |
> | :FasUserGroup: Race | Humanoid (orc) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 16 | 7 | 11 | 10 |
| **Mod** | +3 | +1 | +3 | -2 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Orc
**Skills:** Intimidation +2

---

### Traits

**Aggressive.** As a bonus action, the orc can move up to its speed toward a hostile creature that it can see.


---

### Actions

**Greataxe.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 9 (1d12 + 3) slashing damage.

**Javelin.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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