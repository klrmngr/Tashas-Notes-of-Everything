---
type: pc
race: "Beast"
class:
 - "Giant Hyena"
subClass:
 - "CR 1"
cover: "Giant Hyena.png"
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
###### Giant Hyena
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Hyena.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 2 | 12 | 7 |
| **Mod** | +3 | +2 | +2 | -4 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Actions

**Bite.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Piercing damage.


---

### Bonus Actions

**Rampage (1/Day).** Immediately after dealing damage to a creature that was already Bloodied, the hyena can move up to half its Speed, and it makes one Bite attack.


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