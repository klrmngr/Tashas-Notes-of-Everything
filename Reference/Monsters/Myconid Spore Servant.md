---
type: pc
race: "Plant"
class:
 - "Myconid Spore Servant"
subClass:
 - "CR 1"
cover: "Myconid Spore Servant.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/1
  - source/xmm
---
###### Myconid Spore Servant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Myconid Spore Servant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 16 | 2 | 6 | 1 |
| **Mod** | +3 | +1 | +3 | -4 | -2 | -5 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., passive Perception 8
**Languages:** telepathy 30 ft.
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; frightened; paralyzed; poisoned

---

### Actions

**Slam.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Bludgeoning damage plus 2 (1d4) Poison damage.


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