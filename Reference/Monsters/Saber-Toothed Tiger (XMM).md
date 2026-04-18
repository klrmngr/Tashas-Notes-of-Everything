---
type: pc
race: "Beast"
class:
 - "Saber-Toothed Tiger"
subClass:
 - "CR 2"
cover: "Saber-Toothed Tiger.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/2
  - source/xmm
---
###### Saber-Toothed Tiger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Saber-Toothed Tiger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 17 | 15 | 3 | 12 | 8 |
| **Mod** | +4 | +3 | +2 | -4 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** —
**Saving Throws:** Str +6, Dex +5
**Skills:** Perception +5, Stealth +7

---

### Traits

**Running Leap.** With a 10-foot running start, the tiger can Long Jump up to 25 feet.


---

### Actions

**Multiattack.** The tiger makes two Rend attacks.

**Rend.** m +6, reach 5 ft. *Hit:* 11 (2d6 + 4) Slashing damage.


---

### Bonus Actions

**Nimble Escape.** The tiger takes the Disengage or Hide action.


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