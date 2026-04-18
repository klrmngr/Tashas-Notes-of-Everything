---
type: pc
race: "Humanoid"
class:
 - "Zhentilar Soldier"
subClass:
 - "CR 1"
cover: "Zhentilar Soldier.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/fraif
---
###### Zhentilar Soldier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Zhentilar Soldier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 13 | 10 | 11 | 11 |
| **Mod** | +2 | +2 | +1 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Saving Throws:** Dex +4, Con +3
**Skills:** Acrobatics +4, Athletics +4

---

### Actions

**Multiattack.** The Zhentilar makes two attacks, using Shortsword or Pistol in any combination. It can replace one attack with a use of Knock Down.

**Shortsword.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 2 (1d4) Poison damage.

**Pistol.** r +4, range 80/320 ft. *Hit:* 7 (1d10 + 2) Piercing damage.

**Knock Down.** str DC 12, one creature within 5 feet that the Zhentilar can see.  4 (1d4 + 2) Bludgeoning damage. If the target is a Medium or smaller creature, it has the Prone condition.


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