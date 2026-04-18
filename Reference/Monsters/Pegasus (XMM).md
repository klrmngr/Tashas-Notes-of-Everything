---
type: pc
race: "Celestial"
class:
 - "Pegasus"
subClass:
 - "CR 2"
cover: "Pegasus.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/2
  - source/xmm
---
###### Pegasus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Pegasus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 10 | 15 | 13 |
| **Mod** | +4 | +2 | +3 | +0 | +2 | +1 |

**Speed:** 60 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** understands Celestial, Common, Elvish, and Sylvan but can't speak
**Saving Throws:** Dex +4, Con +5, Wis +4, Cha +3
**Skills:** Perception +6

---

### Actions

**Hooves.** m +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Bludgeoning damage plus 5 (2d4) Radiant damage.


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