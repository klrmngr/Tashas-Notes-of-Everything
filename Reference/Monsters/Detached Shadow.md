---
type: pc
race: "Fey"
class:
 - "Detached Shadow"
subClass:
 - "CR —"
cover: "Detached Shadow.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/—
  - source/wbtw
---
###### Detached Shadow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Detached Shadow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | — |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Actions

**Strength Drain.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 9 (2d6 + 2) necrotic damage, and the target's Strength score is reduced by 1d4. The target falls unconscious if this reduces its Strength to 0. The creature regains consciousness and the reduction to its Strength score disappears after it finishes a short or long rest.


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