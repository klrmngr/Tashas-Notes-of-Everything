---
type: pc
race: "Beast"
class:
 - "Giant Spider"
subClass:
 - "CR 1"
cover: "Giant Spider.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1
  - source/xmm
---
###### Giant Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 26 (4d10 + 4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 12 | 2 | 11 | 4 |
| **Mod** | +2 | +3 | +1 | -4 | +0 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4, Stealth +7

---

### Traits

**Spider Climb.** The spider can climb difficult surfaces, including along ceilings, without needing to make an ability check.

**Web Walker.** The spider ignores movement restrictions caused by webs, and it knows the location of any other creature in contact with the same web.


---

### Actions

**Bite.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Piercing damage plus 7 (2d6) Poison damage.

**Web (Recharge 5–6).** dex DC 13, one creature the spider can see within 60 feet.  The target has the Restrained condition until the web is destroyed (AC 10; HP 5; Vulnerability to Fire damage; Immunity to Poison and Psychic damage).


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