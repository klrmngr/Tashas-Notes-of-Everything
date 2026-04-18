---
type: pc
race: "Fey"
class:
 - "Pixie"
subClass:
 - "CR 1/4"
cover: "Pixie.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1-4
  - source/xmm
---
###### Pixie
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Pixie.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 9 (6d4 - 6) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 20 | 8 | 10 | 14 | 15 |
| **Mod** | -4 | +5 | -1 | +0 | +2 | +2 |

**Speed:** 10 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Sylvan
**Skills:** Perception +4, Stealth +7

---

### Traits

**Magic Resistance.** The pixie has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Faerie Dust.** m,r +4, reach 5 ft. or range 60 ft. *Hit:* 1 Radiant damage, and the target has the Charmed or Poisoned condition (pixie's choice) until the start of the pixie's next turn.


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