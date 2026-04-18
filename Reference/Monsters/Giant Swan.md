---
type: pc
race: "Beast"
class:
 - "Giant Swan"
subClass:
 - "CR 1"
cover: "Giant Swan.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1
  - source/wbtw
---
###### Giant Swan
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Giant Swan.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 26 (4d10 + 4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 13 | 8 | 14 | 10 |
| **Mod** | +3 | +3 | +1 | -1 | +2 | +0 |

**Speed:** 10 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Auran, Common
**Skills:** Perception +4

---

### Traits

**Keen Sight.** The swan has advantage on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The swan makes two attacks with its beak.

**Beak.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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