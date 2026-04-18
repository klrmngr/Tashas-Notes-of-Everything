---
type: pc
race: "Humanoid (human)"
class:
 - "Uthgardt Barbarian Leader"
subClass:
 - "CR —"
cover: "Uthgardt Barbarian Leader.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/skt
---
###### Uthgardt Barbarian Leader
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Uthgardt Barbarian Leader.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +2 | +0 | +0 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** Bothii, Common, Elvish

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