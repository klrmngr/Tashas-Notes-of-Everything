---
type: pc
race: "Aberration (gith)"
class:
 - "Githzerai Psion"
subClass:
 - "CR 12"
cover: "Githzerai Psion.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/12
  - source/xmm
---
###### Githzerai Psion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Githzerai Psion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Aberration (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 169 (26d8 + 52) |
> | :FasUserGroup: Race | Aberration (gith) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 15 | 19 | 18 | 14 |
| **Mod** | +1 | +4 | +2 | +4 | +4 | +2 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common, Gith
**Saving Throws:** Str +5, Dex +8, Int +8, Wis +8
**Skills:** Arcana +8, Insight +8, Perception +8

---

### Actions

**Multiattack.** The githzerai makes three Psychic Warp attacks.

**Psychic Warp.** m,r +8, reach 5 ft. or range 120 ft. *Hit:* 26 (4d10 + 4) Psychic damage, and the target has the githzerai's choice of (A) the Charmed condition until the start of the githzerai's next turn or (B) the Prone condition, provided the target is a Large or smaller creature.


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