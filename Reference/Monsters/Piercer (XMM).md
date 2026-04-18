---
type: pc
race: "Aberration"
class:
 - "Piercer"
subClass:
 - "CR 1/2"
cover: "Piercer.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/1-2
  - source/xmm
---
###### Piercer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Piercer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 22 (3d8 + 9) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 13 | 16 | 1 | 7 | 3 |
| **Mod** | +1 | +1 | +3 | -5 | -2 | -4 |

**Speed:** 5 ft., climb 15 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 60 ft., passive Perception 8
**Languages:** —
**Skills:** Stealth +5

---

### Traits

**Spider Climb.** The piercer can climb difficult surfaces, including along ceilings, without needing to make an ability check.


---

### Actions

**Bite.** m +3, reach 5 ft. *Hit:* 5 (1d8 + 1) Piercing damage.

**Drop.** The piercer falls. dex DC 11, one creature directly underneath the piercer.  10 (3d6) Piercing damage.  The piercer reduces any damage it takes from the fall by 20.


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