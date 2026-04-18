---
type: pc
race: "Plant"
class:
 - "Tribal Warrior Spore Servant"
subClass:
 - "CR —"
cover: "Tribal Warrior Spore Servant.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/—
  - source/idrotf
---
###### Tribal Warrior Spore Servant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Tribal Warrior Spore Servant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | — |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 11 | 12 | 2 | 6 | 1 |
| **Mod** | +1 | +0 | +1 | -4 | -2 | -5 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius)
**Languages:** —
**Condition Immunities:** blinded; charmed; frightened; paralyzed

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