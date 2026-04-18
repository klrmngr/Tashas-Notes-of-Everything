---
type: pc
race: "Humanoid (wizard)"
class:
 - "Mage"
subClass:
 - "CR 6"
cover: "Mage.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/xmm
---
###### Mage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Mage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 81 (18d8) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 11 | 17 | 12 | 11 |
| **Mod** | -1 | +2 | +0 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common and any three languages
**Saving Throws:** Int +6, Wis +4
**Skills:** Arcana +6, History +6, Perception +4

---

### Actions

**Multiattack.** The mage makes three Arcane Burst attacks.

**Arcane Burst.** m,r +6, reach 5 ft. or range 120 ft. *Hit:* 16 (3d8 + 3) Force damage.


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