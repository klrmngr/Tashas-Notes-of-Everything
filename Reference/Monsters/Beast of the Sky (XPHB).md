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
  - source/xphb
---
###### Beast of the Sky
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
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
> | :FasHeart: HP | 4 plus four times your Ranger level (the beast has a number of Hit Dice [d6s] equal to your Ranger level) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 16 | 13 | 8 | 14 | 11 |
| **Mod** | -2 | +3 | +1 | -1 | +2 | +0 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** understands the languages you know

---

### Traits

**Flyby.** The beast doesn't provoke Opportunity Attacks when it flies out of an enemy's reach.

**Primal Bond.** Add your Proficiency Bonus to any ability check or saving throw the beast makes.


---

### Actions

**Beast's Strike.** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d4 + 3 plus your Wisdom modifier Slashing damage.


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