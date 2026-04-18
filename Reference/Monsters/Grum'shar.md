---
type: pc
race: "Humanoid (half-orc)"
class:
 - "Grum'shar"
subClass:
 - "CR 1/4"
cover: "Grum'shar.png"
campaign:
locations:
tags:
  - race/half-orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/wdh
---
###### Grum'shar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Grum'shar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid (half-orc) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 14 | 10 | 11 |
| **Mod** | +0 | +0 | +0 | +2 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Orc
**Skills:** Arcana +4, History +4

---

### Traits

**Relentless Endurance.** When reduced to 0 hit points, Grum'shar drops to 1 hit point instead. He can only do this once per long rest.


---

### Actions

**Dagger.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) piercing damage. Or Ranged Weapon Attack: +2 to hit, range 20/60 ft., one target. *Hit:* 2 (1d4) piercing damage.


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