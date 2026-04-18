---
type: pc
race: "Beast"
class:
 - "Space Guppy"
subClass:
 - "CR 0"
cover: "Space Guppy.png"
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
###### Space Guppy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Space Guppy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 3 (1d6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 16 | 10 | 1 | 10 | 1 |
| **Mod** | -4 | +3 | +0 | -5 | +0 | -5 |

**Speed:** 0 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —

---

### Traits

**Air Envelope.** If it has at least 1 hit point, the guppy can generate an air envelope around itself when in a vacuum. This air envelope can sustain the guppy and one other Tiny creature in its space indefinitely.

**Flyby.** The guppy doesn't provoke opportunity attacks when it flies out of an enemy's reach.


---

### Actions

**Tail Slap.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 1 bludgeoning damage.


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