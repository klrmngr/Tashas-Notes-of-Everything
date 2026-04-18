---
type: pc
race: "Humanoid"
class:
 - "Noble"
subClass:
 - "CR 1/8"
cover: "Noble.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-8
  - source/xmm
---
###### Noble
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Noble.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 11 | 12 | 14 | 16 |
| **Mod** | +0 | +1 | +0 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus two other languages
**Skills:** Deception +5, Insight +4, Persuasion +5

---

### Actions

**Rapier.** m +3, reach 5 ft. *Hit:* 5 (1d8 + 1) Piercing damage.


---

### Reactions

**Parry.**  The noble is hit by a melee attack roll while holding a weapon.  The noble adds 2 to its AC against that attack, possibly causing it to miss.


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