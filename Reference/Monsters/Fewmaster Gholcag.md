---
type: pc
race: "Giant"
class:
 - "Fewmaster Gholcag"
subClass:
 - "CR 2"
cover: "Fewmaster Gholcag.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/large
  - cr/2
  - source/dsotdq
---
###### Fewmaster Gholcag
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Fewmaster Gholcag.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Giant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (scale mail) |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 8 | 16 | 5 | 7 | 7 |
| **Mod** | +4 | -1 | +3 | -3 | -2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** Common, Giant

---

### Actions

**Greatclub.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage.

**Javelin.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.


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