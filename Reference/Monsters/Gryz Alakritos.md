---
type: pc
race: "Humanoid (goblin, wizard)"
class:
 - "Gryz Alakritos"
subClass:
 - "CR —"
cover: "Gryz Alakritos.png"
campaign:
locations:
tags:
  - race/goblin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/crcotn
---
###### Gryz Alakritos
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Gryz Alakritos.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (goblin, wizard) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | — |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Humanoid (goblin, wizard) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

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