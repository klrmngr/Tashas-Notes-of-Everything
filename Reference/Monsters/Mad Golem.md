---
type: pc
race: "Creature"
class:
 - "Mad Golem"
subClass:
 - "CR 12"
cover: "Mad Golem.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/huge
  - cr/12
  - source/wdmm
---
###### Mad Golem
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Mad Golem.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Creature |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | — |
> | :FasHeart: HP | 264 (23d12 + 115) |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 9 | 10 | 9 |
| **Mod** | +0 | +0 | +0 | -1 | +0 | -1 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** understands Abyssal, Celestial, Common, Draconic, Dwarvish, Elvish, Infernal, and Undercommon but can't speak

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