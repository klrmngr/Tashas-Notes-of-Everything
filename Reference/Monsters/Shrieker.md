---
type: pc
race: "Plant"
class:
 - "Shrieker"
subClass:
 - "CR 0"
cover: "Shrieker.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/0
  - source/mm
---
###### Shrieker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Shrieker.png]]
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
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 1 | 10 | 1 | 3 | 1 |
| **Mod** | -5 | -5 | +0 | -5 | -4 | -5 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Condition Immunities:** blinded; deafened; frightened

---

### Traits

**False Appearance.** While the shrieker remains motionless, it is indistinguishable from an ordinary fungus.


---

### Reactions

**Shriek.** When bright light or a creature is within 30 feet of the shrieker, it emits a shriek audible within 300 feet of it. The shrieker continues to shriek until the disturbance moves out of range and for 1d4 of the shrieker's turns afterward.


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