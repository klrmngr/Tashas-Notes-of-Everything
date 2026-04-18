---
type: pc
race: "Humanoid (elf)"
class:
 - "Derwyth"
subClass:
 - "CR 2"
cover: "Derwyth.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/qftis
---
###### Derwyth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Derwyth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 11; 16 with barkskin |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 13 | 12 | 15 | 11 |
| **Mod** | +0 | +1 | +1 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60, passive Perception 14
**Languages:** Common, Elvish
**Skills:** Medicine +4, Nature +3, Perception +4

---

### Traits

**Tree Shape (2/Day).** Over the course of 1 minute, Derwyth can magically transform into a Huge or smaller tree and remain in that form for 24 hours or until she ends this transformation early (no action required). Her equipment melds into her new form. While in this form, her Armor Class is 16, she has the incapacitated condition, and she can't move or speak.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +2 to hit (+4 to hit with shillelagh), reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, 4 (1d8) bludgeoning damage if wielded with two hands, or 6 (1d8 + 2) bludgeoning damage with shillelagh.


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