---
type: pc
race: "Beast"
class:
 - "Beast of the Land"
subClass:
 - "CR —"
cover: "Beast of the Land.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/—
  - source/xphb
---
###### Beast of the Land
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Beast of the Land.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Beast |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 5 plus five times your Ranger level (the beast has a number of Hit Dice [d8s] equal to your Ranger level) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 15 | 8 | 14 | 11 |
| **Mod** | +2 | +2 | +2 | -1 | +2 | +0 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** understands the languages you know

---

### Traits

**Primal Bond.** Add your Proficiency Bonus to any ability check or saving throw the beast makes.


---

### Actions

**Beast's Strike.** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d8 + 2 plus your Wisdom modifier Bludgeoning, Piercing, or Slashing damage (your choice when you summon the beast). If the beast moved at least 20 feet straight toward the target before the hit, the target takes an extra 1d6 damage of the same type, and the target has the Prone condition if it is a Large or smaller creature.


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