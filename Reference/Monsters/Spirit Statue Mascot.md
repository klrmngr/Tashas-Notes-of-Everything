---
type: pc
race: "Construct"
class:
 - "Spirit Statue Mascot"
subClass:
 - "CR 1/4"
cover: "Spirit Statue Mascot.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-4
  - source/scc
---
###### Spirit Statue Mascot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Spirit Statue Mascot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 9 | 15 | 12 | 13 | 8 |
| **Mod** | +2 | -1 | +2 | +1 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any languages it knew in life
**Skills:** Arcana +5, History +5, Perception +3

---

### Traits

**Death Burst.** When the spirit statue is reduced to 0 hit points, the statue crumbles, and the spirit returns to the afterlife in a burst of ghostly white flame. Each creature within 5 feet of it must succeed on a DC 12 Constitution saving throw or take 3 (1d6) radiant damage.


---

### Actions

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.

**Counsel of the Past (2/Day).** The spirit statue touches one creature. Once within the next 10 minutes, that creature can roll a d4 and add the number rolled to one ability check of its choice, immediately after rolling the d20.


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