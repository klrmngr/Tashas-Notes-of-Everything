---
type: pc
race: "Giant"
class:
 - "Chief Guh"
subClass:
 - "CR 5"
cover: "Chief Guh.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/5
  - source/skt
---
###### Chief Guh
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Chief Guh.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 9 (natural armor) |
> | :FasHeart: HP | 160 (10d12 + 40) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 1 | 19 | 5 | 9 | 6 |
| **Mod** | +5 | -5 | +4 | -3 | -1 | -2 |

**Speed:** 0 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Giant, Goblin
**Skills:** Perception +2

---

### Actions

**Multiattack.** The giant makes two greatclub attacks or two unarmed attacks.

**Greatclub.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 18 (3d8 + 5) bludgeoning damage.

**Unarmed Attack.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 12 (3d4 + 5) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +8 to hit, range 60/240 ft., one target. *Hit:* 21 (3d10 + 5) bludgeoning damage.


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