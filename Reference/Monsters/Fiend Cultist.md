---
type: pc
race: "Humanoid"
class:
 - "Fiend Cultist"
subClass:
 - "CR 8"
cover: "Fiend Cultist.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/8
  - source/xmm
---
###### Fiend Cultist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Fiend Cultist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 127 (17d8 + 51) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 15 | 16 | 12 | 18 | 10 |
| **Mod** | +4 | +2 | +3 | +1 | +4 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 90 ft. (unimpeded by magical Darkness), passive Perception 17
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Con +6, Wis +7
**Skills:** Perception +7, Religion +4

---

### Actions

**Multiattack.** The cultist makes three Pact Axe attacks.

**Pact Axe.** m +7, reach 5 ft. *Hit:* 10 (1d12 + 4) Slashing damage plus 13 (3d8) Fire damage.


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