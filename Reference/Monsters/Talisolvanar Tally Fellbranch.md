---
type: pc
race: "Humanoid (half-elf)"
class:
 - "Talisolvanar "Tally" Fellbranch"
subClass:
 - "CR 0"
cover: "Talisolvanar "Tally" Fellbranch.png"
campaign:
locations:
tags:
  - race/half-elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/0
  - source/wdh
---
###### Talisolvanar "Tally" Fellbranch
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Talisolvanar "Tally" Fellbranch.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 4 (1d8) |
> | :FasUserGroup: Race | Humanoid (half-elf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Elvish

---

### Traits

**Fey Ancestry.** Tally has advantage on saving throws against being charmed, and magic can't put him to sleep.


---

### Actions

**Club.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.


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