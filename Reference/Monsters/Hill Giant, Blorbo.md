---
type: pc
race: "Giant"
class:
 - "Hill Giant, Blorbo"
subClass:
 - "CR 4"
cover: "Hill Giant, Blorbo.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/4
  - source/awm
---
###### Hill Giant, Blorbo
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Hill Giant, Blorbo.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 105 |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 8 | 19 | 5 | 9 | 6 |
| **Mod** | +5 | -1 | +4 | -3 | -1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Actions

**Multiattack.** The giant makes two greatclub attacks.

**Greatclub.** Melee Weapon Attack: +8 to hit, one target. *Hit:* 18 (3d8 + 5) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +8 to hit, one target. *Hit:* 21 (3d10 + 5) bludgeoning damage.


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