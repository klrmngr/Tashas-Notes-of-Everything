---
type: pc
race: "Plant"
class:
 - "Vine Blight Tangler"
subClass:
 - "CR 1/2"
cover: "Vine Blight Tangler.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-2
  - source/wtthc
---
###### Vine Blight Tangler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Vine Blight Tangler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 19 (3d8) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | WttHC |

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

**Constricting Vine.** m +4, reach 10 ft. *Hit:* 1d10 + 2 Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 12) from one of three vines.

**Entangling Vines (Recharge 5–6).** Grasping vines momentarily appear on each enemy in a 10-foot-radius Sphere centered on a point of the blight's choice within 60 feet of it. Each target must succeed on a DC 12 Strength saving throw or have the Restrained condition until the start of the blight's next turn.


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