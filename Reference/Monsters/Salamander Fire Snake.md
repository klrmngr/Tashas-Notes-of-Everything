---
type: pc
race: "Elemental"
class:
 - "Salamander Fire Snake"
subClass:
 - "CR 1"
cover: "Salamander Fire Snake.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/1
  - source/xmm
---
###### Salamander Fire Snake
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Salamander Fire Snake.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 11 | 7 | 10 | 8 |
| **Mod** | +1 | +2 | +0 | -2 | +0 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** understands Primordial but can't speak
**Damage Vulnerabilities:** cold
**Damage Immunities:** fire

---

### Traits

**Fire Aura.** At the end of each of the salamander's turns, each creature of the salamander's choice in a 5-foot Emanation originating from the salamander takes 3 (1d6) Fire damage.


---

### Actions

**Bite.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Piercing damage plus 3 (1d6) Fire damage.


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