---
type: pc
race: "Beast"
class:
 - "Giant Snapping Turtle"
subClass:
 - "CR 3"
cover: "Giant Snapping Turtle.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/3
  - source/toa
---
###### Giant Snapping Turtle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Giant Snapping Turtle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor); 12 while prone |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 14 | 2 | 12 | 5 |
| **Mod** | +4 | +0 | +2 | -4 | +1 | -3 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** —

---

### Traits

**Amphibious.** The turtle can breathe air and water.

**Stable.** Whenever an effect knocks the turtle prone, it can make a DC 10 Constitution saving throw to avoid being knocked prone. A prone turtle is upside down. To stand up, it must succeed on a DC 10 Dexterity check on its turn and then use all its movement for that turn.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 18 (4d6 + 4) slashing damage.


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