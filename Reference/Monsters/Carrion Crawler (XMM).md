---
type: pc
race: "Monstrosity"
class:
 - "Carrion Crawler"
subClass:
 - "CR 2"
cover: "Carrion Crawler.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/2
  - source/xmm
---
###### Carrion Crawler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Carrion Crawler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 51 (6d10 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 13 | 16 | 1 | 12 | 5 |
| **Mod** | +2 | +1 | +3 | -5 | +1 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5

---

### Traits

**Spider Climb.** The carrion crawler can climb difficult surfaces, including along ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The carrion crawler uses Paralyzing Tentacles and makes one Bite attack.

**Bite.** m +4, reach 5 ft. *Hit:* 7 (2d4 + 2) Piercing damage plus 3 (1d6) Poison damage.

**Paralyzing Tentacles.** con DC 12, one creature the carrion crawler can see within 10 feet.  The target has the Poisoned condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. While Poisoned, the target has the Paralyzed condition.


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