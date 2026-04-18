---
type: pc
race: "Giant"
class:
 - "Cloud Giant"
subClass:
 - "CR 9"
cover: "Cloud Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/9
  - source/xmm
---
###### Cloud Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Cloud Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 22 | 12 | 16 | 16 |
| **Mod** | +8 | +0 | +6 | +1 | +3 | +3 |

**Speed:** 40 ft., fly 20 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 21
**Languages:** Common, Giant
**Saving Throws:** Con +10, Wis +7
**Skills:** Insight +7, Perception +11

---

### Actions

**Multiattack.** The giant makes two attacks, using Thunderous Mace or Thundercloud in any combination. It can replace one attack with a use of Spellcasting to cast Fog Cloud.

**Thunderous Mace.** m +12, reach 10 ft. *Hit:* 21 (3d8 + 8) Bludgeoning damage plus 7 (2d6) Thunder damage.

**Thundercloud.** r +12, range 240 ft. *Hit:* 18 (3d6 + 8) Thunder damage, and the target has the Incapacitated condition until the end of its next turn.


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