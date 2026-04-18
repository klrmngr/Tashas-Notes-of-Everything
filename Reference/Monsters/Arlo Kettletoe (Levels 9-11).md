---
type: pc
race: "Humanoid (halfling)"
class:
 - "Arlo Kettletoe (Levels 9-11)"
subClass:
 - "CR —"
cover: "Arlo Kettletoe (Levels 9-11).png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/kftgv
---
###### Arlo Kettletoe (Levels 9-11)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Arlo Kettletoe (Levels 9-11).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (halfling) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | — |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | Keys from the Golden Vault |

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