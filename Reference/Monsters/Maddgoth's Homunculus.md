---
type: pc
race: "Creature"
class:
 - "Maddgoth's Homunculus"
subClass:
 - "CR 2"
cover: "Maddgoth's Homunculus.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/large
  - cr/2
  - source/wdmm
---
###### Maddgoth's Homunculus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Maddgoth's Homunculus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Creature |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | — |
> | :FasHeart: HP | 55 (10d10) |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +2 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** Abyssal, Common, Draconic, Gnomish but can't speak

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