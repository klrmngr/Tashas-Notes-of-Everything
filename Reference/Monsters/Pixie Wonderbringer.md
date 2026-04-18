---
type: pc
race: "Fey"
class:
 - "Pixie Wonderbringer"
subClass:
 - "CR 5"
cover: "Pixie Wonderbringer.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/5
  - source/xmm
---
###### Pixie Wonderbringer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Pixie Wonderbringer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 60 (24d4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 20 | 10 | 11 | 14 | 18 |
| **Mod** | -4 | +5 | +0 | +0 | +2 | +4 |

**Speed:** 10 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Elvish, Sylvan
**Skills:** Arcana +3, Perception +5, Stealth +8

---

### Traits

**Magic Resistance.** The pixie has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The pixie makes two Faerie Dust attacks.

**Faerie Dust.** m,r +7, reach 5 ft. or range 60 ft. *Hit:* 15 (2d10 + 4) Radiant damage, and the target has the Charmed or Poisoned condition (pixie's choice) until the start of the pixie's next turn.


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