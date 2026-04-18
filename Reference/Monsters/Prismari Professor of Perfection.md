---
type: pc
race: "Humanoid (sorcerer)"
class:
 - "Prismari Professor of Perfection"
subClass:
 - "CR 7"
cover: "Prismari Professor of Perfection.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/scc
---
###### Prismari Professor of Perfection
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Prismari Professor of Perfection.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (sorcerer) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Humanoid (sorcerer) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 15 | 15 | 13 | 19 |
| **Mod** | +2 | +3 | +2 | +2 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus any four languages
**Saving Throws:** Dex +6, Int +5, Wis +4, Cha +7
**Skills:** Acrobatics +6, Arcana +5, Athletics +5, Perception +4, Performance +10
**Damage Resistances:** cold

---

### Traits

**Water Walking.** The professor can walk across water and other liquids as if they were solid ground.


---

### Actions

**Multiattack.** The professor makes three Tidal Strike attacks.

**Tidal Strike.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 13 (2d8 + 4) cold damage.


---

### Bonus Actions

**Rushing Wave.** The professor is momentarily surrounded by a swirling wave of water and moves up to 30 feet. When the professor moves within 5 feet of any other creature during this bonus action, that creature must succeed on a DC 15 Strength saving throw, or the creature is knocked prone and it can't take reactions until the start of its next turn. A creature can suffer this effect only once during a turn.


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