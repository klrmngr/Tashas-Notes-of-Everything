---
type: pc
race: "Humanoid (human)"
class:
 - "Tarak"
subClass:
 - "CR 1"
cover: "Tarak.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/dosi
---
###### Tarak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DoSI
___

> [!infobox|no-t right]
> ![[Tarak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | DoSI |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 10 | 12 | 14 | 16 |
| **Mod** | +0 | +3 | +0 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Draconic, Thieves' cant
**Skills:** Deception +5, Insight +4, Medicine +4, Nature +3

---

### Actions

**Multiattack.** Tarak makes three Dagger attacks.

**Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


---

### Bonus Actions

**Cunning Action.** Tarak takes the Dash, Disengage, or Hide action.


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