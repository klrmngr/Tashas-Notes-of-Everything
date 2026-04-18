---
type: pc
race: "Beast"
class:
 - "Spider"
subClass:
 - "CR 0"
cover: "Spider.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/tiny
  - cr/0
  - source/xmm
---
###### Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Beast |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 1 (1d4 - 1) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 14 | 8 | 1 | 10 | 2 |
| **Mod** | -4 | +2 | -1 | -5 | +0 | -4 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 30 ft., passive Perception 10
**Languages:** —
**Skills:** Stealth +4

---

### Traits

**Spider Climb.** The spider can climb difficult surfaces, including along ceilings, without needing to make an ability check.

**Web Walker.** The spider ignores movement restrictions caused by webs, and the spider knows the location of any other creature in contact with the same web.


---

### Actions

**Bite.** m +4, reach 5 ft. *Hit:* 1 Piercing damage plus 2 (1d4) Poison damage.


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