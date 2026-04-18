---
type: pc
race: "Plant"
class:
 - "Vine Blight"
subClass:
 - "CR 1/2"
cover: "Vine Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-2
  - source/xmm
---
###### Vine Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Vine Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 8 | 14 | 5 | 10 | 3 |
| **Mod** | +2 | -1 | +2 | -3 | +0 | -4 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 10
**Languages:** Common
**Skills:** Stealth +1
**Condition Immunities:** deafened

---

### Actions

**Constricting Vine.** m +4, reach 10 ft. *Hit:* 6 (1d8 + 2) Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 12). Until the grapple ends, the target takes 4 (1d8) Bludgeoning damage at the start of each of its turns, and the blight can't make Constricting Vine attacks.


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