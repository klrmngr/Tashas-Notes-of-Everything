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
  - source/mm
---
###### Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
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
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 14 | 8 | 1 | 10 | 2 |
| **Mod** | -4 | +2 | -1 | -5 | +0 | -4 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 10
**Languages:** —
**Skills:** Stealth +4

---

### Traits

**Spider Climb.** The spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** While in contact with a web, the spider knows the exact location of any other creature in contact with the same web.

**Web Walker.** The spider ignores movement restrictions caused by webbing.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 1 piercing damage, and the target must succeed on a DC 9 Constitution saving throw or take 2 (1d4) poison damage.


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