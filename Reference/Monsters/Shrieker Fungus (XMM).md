---
type: pc
race: "Plant"
class:
 - "Shrieker Fungus"
subClass:
 - "CR 0"
cover: "Shrieker Fungus.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/0
  - source/xmm
---
###### Shrieker Fungus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Shrieker Fungus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 5 |
> | :FasHeart: HP | 13 (3d8) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 1 | 10 | 1 | 3 | 1 |
| **Mod** | -5 | -5 | +0 | -5 | -4 | -5 |

**Speed:** 5 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., passive Perception 6
**Languages:** —
**Condition Immunities:** blinded; charmed; deafened; frightened

---

### Reactions

**Shriek.**  A creature or a source of Bright Light moves within 30 feet of the shrieker.  The shrieker emits a shriek audible within 300 feet of itself for 1 minute or until the shrieker dies.


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