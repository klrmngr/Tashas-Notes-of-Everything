---
type: pc
race: "Aberration"
class:
 - "Grick Ancient"
subClass:
 - "CR 7"
cover: "Grick Ancient.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/7
  - source/xmm
---
###### Grick Ancient
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Grick Ancient.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 135 (18d10 + 36) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 15 | 4 | 14 | 9 |
| **Mod** | +4 | +3 | +2 | -3 | +2 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** —
**Skills:** Stealth +6

---

### Actions

**Multiattack.** The grick makes one Beak attack, one Slam attack, and one Tentacles attack.

**Beak.** m +7, reach 10 ft. *Hit:* 22 (4d8 + 4) Piercing damage.

**Slam.** m +7, reach 10 ft. *Hit:* 7 (1d6 + 4) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.

**Tentacles.** m +7, reach 10 ft. *Hit:* 15 (2d10 + 4) Slashing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from all four tentacles.


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