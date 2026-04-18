---
type: pc
race: "Beast"
class:
 - "Fastieth"
subClass:
 - "CR 1/4"
cover: "Fastieth.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1-4
  - source/erlw
---
###### Fastieth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Fastieth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Beast |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 10 | 4 | 11 | 4 |
| **Mod** | +1 | +4 | +0 | -3 | +0 | -3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —

---

### Traits

**Quickness (Recharge 5–6).** The fastieth can take the Dodge action as a bonus action.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.


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