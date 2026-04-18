---
type: pc
race: "Beast"
class:
 - "Killer Whale"
subClass:
 - "CR 3"
cover: "Killer Whale.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/3
  - source/mm
---
###### Killer Whale
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Killer Whale.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 90 (12d12 + 12) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 13 | 3 | 12 | 7 |
| **Mod** | +4 | +0 | +1 | -4 | +1 | -2 |

**Speed:** swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Traits

**Echolocation.** The whale can't use its blindsight while deafened.

**Hold Breath.** The whale can hold its breath for 30 minutes.

**Keen Hearing.** The whale has advantage on Wisdom (Perception) checks that rely on hearing.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 21 (5d6 + 4) piercing damage.


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