---
type: pc
race: "Humanoid (any race)"
class:
 - "Magewright"
subClass:
 - "CR 0"
cover: "Magewright.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/0
  - source/erlw
---
###### Magewright
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Magewright.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 13 | 10 | 14 | 14 | 12 |
| **Mod** | +0 | +1 | +0 | +2 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus any two languages
**Skills:** Arcana +4

---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.


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