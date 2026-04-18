---
type: pc
race: "Beast"
class:
 - "Black Bear"
subClass:
 - "CR 1/2"
cover: "Black Bear.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1-2
  - source/xmm
---
###### Black Bear
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Black Bear.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Beast |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 14 | 2 | 12 | 7 |
| **Mod** | +2 | +1 | +2 | -4 | +1 | -2 |

**Speed:** 30 ft., climb 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5

---

### Actions

**Multiattack.** The bear makes two Rend attacks.

**Rend.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Slashing damage.


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