---
type: pc
race: "Humanoid (sorcerer)"
class:
 - "Prismari Pledgemage"
subClass:
 - "CR 4"
cover: "Prismari Pledgemage.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/scc
---
###### Prismari Pledgemage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Prismari Pledgemage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (sorcerer) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (sorcerer) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 13 | 12 | 14 | 17 |
| **Mod** | +0 | +2 | +1 | +1 | +2 | +3 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus any two languages
**Saving Throws:** Dex +4, Cha +5
**Skills:** Acrobatics +4, Athletics +4, Performance +7

---

### Traits

**Evasion.** If the pledgemage is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the pledgemage instead takes no damage if it succeeds on the saving throw and only half damage if it fails, provided it isn't incapacitated.


---

### Actions

**Multiattack.** The pledgemage makes two Elemental Strike attacks.

**Elemental Strike.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 12 (3d6 + 2) fire or cold damage (the pledgemage's choice).

**Showstopper (1/Day).** The pledgemage shines with elemental magic, targeting one creature it can see within 60 feet of itself. The target must make a DC 13 Wisdom saving throw. On a failed save, the target takes 28 (8d6) fire or cold damage (the pledgemage's choice) and is stunned until the start of the pledgemage's next turn. On a successful save, the target takes half as much damage and isn't stunned.


---

### Bonus Actions

**Surge of Artistry (Recharge 4–6).** The pledgemage moves up to its speed, surrounding itself with elemental magic as it moves. Until the end of its turn, the pledgemage can move through the space of other creatures. The first time the pledgemage enters a creature's space on a turn, that creature must succeed on a DC 13 Dexterity saving throw or be knocked prone. If the pledgemage ends its turn in another creature's space, the pledgemage takes 5 (1d10) force damage and is pushed into the nearest unoccupied space.


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