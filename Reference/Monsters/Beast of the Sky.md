---
type: pc
race: "Beast"
class:
 - "Beast of the Sky"
subClass:
 - "CR —"
cover: "Beast of the Sky.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/—
  - source/tce
---
###### Beast of the Sky
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Beast of the Sky.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 4 + four times your ranger level (the beast has a number of Hit Dice [d6s] equal to your ranger level) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 16 | 13 | 8 | 14 | 11 |
| **Mod** | -2 | +3 | +1 | -1 | +2 | +0 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** understands the languages you speak

---

### Traits

**Flyby.** The beast doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Primal Bond.** You can add your proficiency bonus to any ability check or saving throw that the beast makes.


---

### Actions

**Shred.** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d4 + 3 + PB slashing damage.


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