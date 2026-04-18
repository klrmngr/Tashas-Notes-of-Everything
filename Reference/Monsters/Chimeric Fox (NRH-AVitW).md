---
type: pc
race: "Beast"
class:
 - "Chimeric Fox"
subClass:
 - "CR 0"
cover: "Chimeric Fox.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/tiny
  - cr/0
  - source/nrh-avitw
---
###### Chimeric Fox
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NRH-AVitW
___

> [!infobox|no-t right]
> ![[Chimeric Fox.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Beast |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 2 (1d4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | NRH-AVitW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 16 | 11 | 3 | 12 | 6 |
| **Mod** | -4 | +3 | +0 | -4 | +1 | -2 |

**Speed:** 30 ft., burrow 5 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +5

---

### Traits

**Chimeric Creation.** The fox has fur that changes color to match its surroundings, giving it advantage on Dexterity (Stealth) checks.

**Keen Hearing.** The fox has advantage on Wisdom (Perception) checks that rely on hearing.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 1 piercing damage.


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