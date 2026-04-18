---
type: pc
race: "Creature"
class:
 - "Armored Saber-Toothed Tiger"
subClass:
 - "CR 3"
cover: "Armored Saber-Toothed Tiger.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/medium
  - cr/3
  - source/cos
---
###### Armored Saber-Toothed Tiger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Armored Saber-Toothed Tiger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Creature |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 17 (half plate armor) |
> | :FasHeart: HP | 84 (7d10 + 14) |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
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