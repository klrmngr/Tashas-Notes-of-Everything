---
type: pc
race: "Beast"
class:
 - "Giant Scorpion"
subClass:
 - "CR 3"
cover: "Giant Scorpion.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/3
  - source/xmm
---
###### Giant Scorpion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Giant Scorpion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 15 | 1 | 9 | 3 |
| **Mod** | +3 | +1 | +2 | -5 | -1 | -4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 9
**Languages:** —

---

### Actions

**Multiattack.** The scorpion makes two Claw attacks and one Sting attack.

**Claw.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 13) from one of two claws.

**Sting.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Piercing damage plus 11 (2d10) Poison damage.


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