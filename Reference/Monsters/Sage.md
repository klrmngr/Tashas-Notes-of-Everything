---
type: pc
race: "Humanoid (any race)"
class:
 - "Sage"
subClass:
 - "CR 1/2"
cover: "Sage.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/cm
---
###### Sage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Sage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 10 | 10 | 18 | 15 | 11 |
| **Mod** | -1 | +0 | +0 | +4 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus any four languages
**Skills:** Arcana +8, History +8, Insight +4, Investigation +8, Medicine +6, Nature +8, Religion +8

---

### Actions

**Shocking Grasp (Cantrip).** Melee Spell Attack: +6 to hit (with advantage if the target is wearing armor made of metal), reach 5 ft., one creature. *Hit:* 9 (2d8) lightning damage, and the target can't take reactions until the start of its next turn.


---

### Reactions

**Shield (1st-Level Spell; 3/Day).** When the sage is hit by an attack or targeted by a magic missile spell, it calls forth an invisible barrier of magical force that protects it. Until the start of its next turn, the sage has a +5 bonus to AC, including against the triggering attack, and it takes no damage from magic missile.


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