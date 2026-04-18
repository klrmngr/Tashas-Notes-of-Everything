---
type: pc
race: "Humanoid"
class:
 - "Noble Prodigy"
subClass:
 - "CR 10"
cover: "Noble Prodigy.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/10
  - source/xmm
---
###### Noble Prodigy
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Noble Prodigy.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 148 (27d8 + 27) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 12 | 15 | 14 | 19 |
| **Mod** | -1 | +3 | +1 | +2 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus two other languages
**Saving Throws:** Dex +7, Con +5, Wis +6, Cha +8
**Skills:** Perception +6, Persuasion +8

---

### Actions

**Multiattack.** The noble makes three Beguiling Strike attacks.

**Beguiling Strike.** m,r +8, reach 5 ft. or range 60 ft. *Hit:* 18 (4d6 + 4) Psychic damage, and the target has the Charmed condition until the start of the noble's next turn.


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