---
type: pc
race: "Plant"
class:
 - "Tree Blight"
subClass:
 - "CR 7"
cover: "Tree Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/7
  - source/xmm
---
###### Tree Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Tree Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 115 (10d12 + 50) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 20 | 6 | 10 | 3 |
| **Mod** | +6 | +0 | +5 | -2 | +0 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 10
**Languages:** understands Common and Druidic but can't speak
**Condition Immunities:** deafened

---

### Actions

**Multiattack.** The blight makes two Branch attacks and uses Grasping Root.

**Branch.** m +9, reach 15 ft. *Hit:* 16 (3d6 + 6) Bludgeoning damage.

**Grasping Root.** str DC 17, one Large or smaller creature the blight can see within 15 feet.  The target is pulled up to 10 feet straight toward the blight and has the Grappled condition (escape DC 16) from one of six roots. Until the grapple ends, the target takes 13 (2d6 + 6) Bludgeoning damage at the start of each of its turns.


---

### Bonus Actions

**Gnash.** dex DC 17, one creature Grappled by the blight.  19 (3d8 + 6) Piercing damage.  Half damage.


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