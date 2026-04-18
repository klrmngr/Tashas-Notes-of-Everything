---
type: pc
race: "Plant"
class:
 - "Awakened Tree"
subClass:
 - "CR 2"
cover: "Awakened Tree.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/2
  - source/xmm
---
###### Awakened Tree
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Awakened Tree.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 59 (7d12 + 14) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 6 | 15 | 10 | 10 | 7 |
| **Mod** | +4 | -2 | +2 | +0 | +0 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common plus one other language
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing

---

### Actions

**Slam.** m +6, reach 10 ft. *Hit:* 13 (2d8 + 4) Bludgeoning damage.


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