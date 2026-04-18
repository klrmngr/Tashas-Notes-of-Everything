---
type: pc
race: "Plant"
class:
 - "Needle Blight"
subClass:
 - "CR 1/4"
cover: "Needle Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-4
  - source/xmm
---
###### Needle Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Needle Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 12 | 13 | 4 | 8 | 3 |
| **Mod** | +1 | +1 | +1 | -3 | -1 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 9
**Languages:** understands Common but can't speak
**Condition Immunities:** deafened

---

### Actions

**Claw.** m +3, reach 5 ft. *Hit:* 6 (2d4 + 1) Slashing damage.

**Needles.** r +3, range 30/60 ft. *Hit:* 6 (2d4 + 1) Piercing damage.


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