---
type: pc
race: "Creature"
class:
 - "Infant Hook Horror"
subClass:
 - "CR 0"
cover: "Infant Hook Horror.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/tiny
  - cr/0
  - source/oota
---
###### Infant Hook Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Infant Hook Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Creature |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 10 (natural armor) |
> | :FasHeart: HP | 4 (1d4 + 2) |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | -1 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

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