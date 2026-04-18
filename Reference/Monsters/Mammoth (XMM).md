---
type: pc
race: "Beast"
class:
 - "Mammoth"
subClass:
 - "CR 6"
cover: "Mammoth.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/6
  - source/xmm
---
###### Mammoth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Mammoth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 126 (11d12 + 55) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 9 | 21 | 3 | 11 | 6 |
| **Mod** | +7 | -1 | +5 | -4 | +0 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Saving Throws:** Str +10, Con +8

---

### Actions

**Multiattack.** The mammoth makes two Gore attacks.

**Gore.** m +10, reach 10 ft. *Hit:* 18 (2d10 + 7) Piercing damage. If the target is a Huge or smaller creature and the mammoth moved 20+ feet straight toward it immediately before the hit, the target has the Prone condition.


---

### Bonus Actions

**Trample.** dex DC 18, one creature within 5 feet that has the Prone condition.  29 (4d10 + 7) Bludgeoning damage.  Half damage.


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