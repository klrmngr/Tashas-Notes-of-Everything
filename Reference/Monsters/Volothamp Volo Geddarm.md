---
type: pc
race: "Humanoid (human)"
class:
 - "Volothamp "Volo" Geddarm"
subClass:
 - "CR 1/4"
cover: "Volothamp "Volo" Geddarm.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/toa
---
###### Volothamp "Volo" Geddarm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Volothamp "Volo" Geddarm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 31 (7d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 12 | 10 | 15 | 11 | 16 |
| **Mod** | -1 | +1 | +0 | +2 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Dwarvish, Elvish
**Saving Throws:** Con +2, Wis +2
**Skills:** Animal Handling +4, Arcana +4, Deception +5, History +4, Insight +2, Investigation +4, Perception +2, Performance +7, Persuasion +7, Sleight Of Hand +3, Survival +2

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