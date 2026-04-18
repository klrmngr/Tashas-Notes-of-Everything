---
type: pc
race: "Aberration"
class:
 - "Gnome Squidling"
subClass:
 - "CR 1/2"
cover: "Gnome Squidling.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/1-2
  - source/idrotf
---
###### Gnome Squidling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Gnome Squidling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 10 (3d6) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 7 | 10 | 4 | 10 | 3 |
| **Mod** | -3 | -2 | +0 | -3 | +0 | -4 |

**Speed:** 15 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands Deep Speech and Gnomish but can't speak, telepathy 60 ft.

---

### Traits

**Magic Resistance.** The squidling has advantage on saving throws against spells and other magical effects.


---

### Actions

**Tentacles.** Melee Weapon Attack: +0 to hit, reach 5 ft., one creature. *Hit:* 5 (2d4) psychic damage. If the target is Medium or smaller, it is grappled (escape DC 7) and must succeed on a DC 7 Intelligence saving throw or be stunned until this grapple ends.

**Extract Brain.** Melee Weapon Attack: +0 to hit, reach 5 ft., one incapacitated creature grappled by the squidling. *Hit:* 27 (5d10) piercing damage. If this damage reduces the target to 0 hit points, the squidling kills the target by extracting and devouring its brain.

**Mind Tickle (Recharge 5–6).** The squidling magically emits psychic energy in a 30-foot cone. Each creature in that area must succeed on a DC 7 Intelligence saving throw or take 2 (1d4) psychic damage and be stunned until the end of its next turn.


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