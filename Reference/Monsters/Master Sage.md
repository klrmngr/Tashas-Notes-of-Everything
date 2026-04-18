---
type: pc
race: "Humanoid (any race)"
class:
 - "Master Sage"
subClass:
 - "CR 5"
cover: "Master Sage.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/cm
---
###### Master Sage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Master Sage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 54 (12d8) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 10 | 10 | 20 | 18 | 11 |
| **Mod** | -1 | +0 | +0 | +5 | +4 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus any five languages
**Skills:** Arcana +11, History +11, Insight +7, Investigation +11, Medicine +10, Nature +11, Religion +11

---

### Actions

**Shocking Grasp (Cantrip).** Melee Spell Attack: +8 to hit (with advantage if the target is wearing armor made of metal), reach 5 ft., one creature. *Hit:* 13 (3d8) lightning damage, and the target can't take reactions until the start of its next turn.

**Lightning Eruption (3/Day).** The sage creates an eruption of magical lightning centered on a point it can see within 150 feet of it. Each creature in a 20-foot-radius sphere centered on that point must make a DC 16 Dexterity saving throw, taking 28 (8d6) lightning damage on a failed save, or half as much damage on a successful one.


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