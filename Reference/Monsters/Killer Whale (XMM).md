---
type: pc
race: "Beast"
class:
 - "Killer Whale"
subClass:
 - "CR 3"
cover: "Killer Whale.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/3
  - source/xmm
---
###### Killer Whale
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Killer Whale.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 90 (12d12 + 12) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 13 | 3 | 12 | 7 |
| **Mod** | +4 | +2 | +1 | -4 | +1 | -2 |

**Speed:** 5 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** Blindsight 120 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +4

---

### Traits

**Hold Breath.** The whale can hold its breath for 30 minutes.


---

### Actions

**Bite.** m +6, reach 5 ft. *Hit:* 21 (5d6 + 4) Piercing damage.


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