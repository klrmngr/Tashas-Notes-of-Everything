---
type: pc
race: "Monstrosity"
class:
 - "Flying Snake"
subClass:
 - "CR 1/8"
cover: "Flying Snake.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/1-8
  - source/xmm
---
###### Flying Snake
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Flying Snake.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 5 (2d4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 11 | 2 | 12 | 5 |
| **Mod** | -3 | +2 | +0 | -4 | +1 | -3 |

**Speed:** 30 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., passive Perception 11
**Languages:** —

---

### Traits

**Flyby.** The snake doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.


---

### Actions

**Bite.** m +4, reach 5 ft. *Hit:* 1 Piercing damage plus 5 (2d4) Poison damage.


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