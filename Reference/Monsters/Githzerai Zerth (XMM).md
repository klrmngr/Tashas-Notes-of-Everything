---
type: pc
race: "Aberration (gith)"
class:
 - "Githzerai Zerth"
subClass:
 - "CR 6"
cover: "Githzerai Zerth.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/6
  - source/xmm
---
###### Githzerai Zerth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Githzerai Zerth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Aberration (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 84 (13d8 + 26) |
> | :FasUserGroup: Race | Aberration (gith) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 15 | 16 | 17 | 12 |
| **Mod** | +1 | +4 | +2 | +3 | +3 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Gith
**Saving Throws:** Str +4, Dex +7, Int +6, Wis +6
**Skills:** Arcana +6, Insight +6, Perception +6

---

### Actions

**Multiattack.** The githzerai makes two Psi Strike attacks.

**Psi Strike.** m +7, reach 5 ft. *Hit:* 11 (2d6 + 4) Bludgeoning damage plus 13 (3d8) Psychic damage.


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