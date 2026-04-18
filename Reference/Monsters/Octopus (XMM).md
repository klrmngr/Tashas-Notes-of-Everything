---
type: pc
race: "Beast"
class:
 - "Octopus"
subClass:
 - "CR 0"
cover: "Octopus.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/0
  - source/xmm
---
###### Octopus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Octopus.png]]
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
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 11 | 3 | 10 | 4 |
| **Mod** | -3 | +2 | +0 | -4 | +0 | -3 |

**Speed:** 5 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 30 ft., passive Perception 12
**Languages:** —
**Skills:** Perception +2, Stealth +6

---

### Traits

**Compression.** The octopus can move through a space as narrow as 1 inch without expending extra movement to do so.

**Water Breathing.** The octopus can breathe only underwater.


---

### Actions

**Tentacles.** m +4, reach 5 ft. *Hit:* 1 Bludgeoning damage.


---

### Reactions

**Ink Cloud (1/Day).**  A creature ends its turn within 5 feet of the octopus while underwater.  The octopus releases ink that fills a 5-foot Cube centered on itself, and the octopus moves up to its Swim Speed. The Cube is Heavily Obscured for 1 minute or until a strong current or similar effect disperses the ink.


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