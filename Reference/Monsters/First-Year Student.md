---
type: pc
race: "Humanoid (wizard)"
class:
 - "First-Year Student"
subClass:
 - "CR 1/2"
cover: "First-Year Student.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-2
  - source/scc
---
###### First-Year Student
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[First-Year Student.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 12 | 13 | 12 | 10 | 11 |
| **Mod** | -1 | +1 | +1 | +1 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common plus any two languages

---

### Traits

**Excited to Be Here.** The student has advantage on initiative rolls.


---

### Actions

**Magic Flare.** Melee or Ranged Spell Attack: +3 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 7 (1d12 + 1) force damage.


---

### Reactions

**Beginner's Luck (2/Day).** When the student fails a saving throw, it can reroll the d20. It must use the new roll.


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