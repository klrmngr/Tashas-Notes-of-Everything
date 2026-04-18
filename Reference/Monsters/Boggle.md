---
type: pc
race: "Fey"
class:
 - "Boggle"
subClass:
 - "CR 1/8"
cover: "Boggle.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/1-8
  - source/mpmm
---
###### Boggle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Boggle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 18 (4d6 + 4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 18 | 13 | 6 | 12 | 7 |
| **Mod** | -1 | +4 | +1 | -2 | +1 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Sylvan
**Skills:** Perception +5, Sleight Of Hand +6, Stealth +6
**Damage Resistances:** fire

---

### Actions

**Pummel.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) bludgeoning damage.

**Oil Puddle.** The boggle creates a puddle of nonflammable oil. The puddle is 1 inch deep and covers the ground in the boggle's space. The puddle is 3 for all creatures except boggles and lasts for 1 hour. The oil has one of the following additional effects of the boggle's choice:
- **Slippery Oil.** Any non-boggle creature that enters the puddle or starts its turn there must succeed on a DC 11 Dexterity saving throw or fall prone.
- **Sticky Oil.** Any non-boggle creature that enters the puddle or starts its turn there must succeed on a DC 11 Strength saving throw or be restrained. On its turn, a creature can use an action to try to extricate itself, ending the effect and moving into the nearest unoccupied space of its choice with a successful DC 11 Strength check.


---

### Bonus Actions

**Boggle Oil.** The boggle excretes nonflammable oil from its pores, giving itself one of the following benefits of its choice until it uses this bonus action again:
- **Slippery Oil.** The boggle has advantage on Dexterity (Acrobatics) checks made to escape bonds and end grapples, and it can move through openings large enough for a Tiny creature without squeezing.
- **Sticky Oil.** The boggle has advantage on Strength (Athletics) checks made to grapple and any ability check made to maintain a hold on another creature, a surface, or an object. The boggle can also climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Dimensional Rift.** The boggle creates an invisible and immobile rift within an opening or frame it can see within 5 feet of it, provided that the space is no bigger than 10 feet on any side. The dimensional rift bridges the distance between that space and a point within 30 feet of it that the boggle can see or specify by distance and direction (such as "30 feet straight up"). While next to the rift, the boggle can see through it and is considered to be next to the destination as well, and anything the boggle puts through the rift (including a portion of its body) emerges at the destination. Only the boggle can use the rift, and it lasts until the end of the boggle's next turn.


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