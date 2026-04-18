---
type: pc
race: "Humanoid (sorcerer)"
class:
 - "Prismari Apprentice"
subClass:
 - "CR 2"
cover: "Prismari Apprentice.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/scc
---
###### Prismari Apprentice
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Prismari Apprentice.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (sorcerer) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (sorcerer) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 13 | 12 | 13 | 15 |
| **Mod** | +0 | +2 | +1 | +1 | +1 | +2 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any two languages
**Saving Throws:** Dex +4, Cha +4
**Skills:** Acrobatics +4, Athletics +4, Performance +6

---

### Actions

**Elemental Strike.** Melee or Ranged Spell Attack: +4 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 10 (3d6) fire or cold damage (the apprentice's choice).


---

### Bonus Actions

**Surge of Artistry (Recharge 4–6).** The apprentice moves up to its speed, surrounding itself with elemental magic as it moves. Until the end of its turn, the apprentice can move through the space of other creatures. The first time the apprentice enters a creature's space on a turn, that creature must succeed on a DC 12 Dexterity saving throw or be knocked prone. If the apprentice ends its turn in another creature's space, the apprentice takes 5 (1d10) force damage and is pushed into the nearest unoccupied space.


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