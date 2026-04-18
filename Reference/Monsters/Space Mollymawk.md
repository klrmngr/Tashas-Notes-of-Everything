---
type: pc
race: "Beast"
class:
 - "Space Mollymawk"
subClass:
 - "CR 0"
cover: "Space Mollymawk.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/0
  - source/bam
---
###### Space Mollymawk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Space Mollymawk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 3 (1d6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 11 | 3 | 12 | 3 |
| **Mod** | -2 | +2 | +0 | -4 | +1 | -4 |

**Speed:** 10 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** —
**Skills:** Perception +5

---

### Traits

**Flyby.** The mollymawk doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Hold Breath.** The mollymawk can hold its breath for 15 minutes.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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