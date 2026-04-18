---
type: pc
race: "Dragon"
class:
 - "Wyvern"
subClass:
 - "CR 6"
cover: "Wyvern.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/6
  - source/xmm
---
###### Wyvern
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Wyvern.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 16 | 5 | 12 | 6 |
| **Mod** | +4 | +0 | +3 | -3 | +1 | -2 |

**Speed:** 30 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4

---

### Actions

**Multiattack.** The wyvern makes one Bite attack and one Sting attack.

**Bite.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Piercing damage.

**Sting.** m +7, reach 10 ft. *Hit:* 11 (2d6 + 4) Piercing damage plus 24 (7d6) Poison damage, and the target has the Poisoned condition until the start of the wyvern's next turn.


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