---
type: pc
race: "Fey"
class:
 - "Swanmay"
subClass:
 - "CR 3"
cover: "Swanmay.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/fraif
---
###### Swanmay
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Swanmay.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 14 | 10 | 16 | 15 |
| **Mod** | +0 | +4 | +2 | +0 | +3 | +2 |

**Speed:** 30 ft., fly 40 ft. ((swan form only)) &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Sylvan
**Saving Throws:** Con +4, Wis +5
**Skills:** Nature +4, Perception +5

---

### Traits

**Flyby (Swan Form Only).** The swanmay doesn't provoke an Opportunity Attack action when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The swanmay makes two attacks, using Beak, Longbow, or Scimitar in any combination.

**Beak (Swan Form Only).** m +6, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage. If the target is a Large or smaller creature, it has the Prone condition.

**Scimitar (Humanoid Form Only).** m +6, reach 5 ft. *Hit:* 11 (2d6 + 4) Slashing damage.

**Longbow (Humanoid Form Only).** r +6, range 150/600 ft. *Hit:* 13 (2d8 + 4) Piercing damage.


---

### Bonus Actions

**Shape-Shift.** The swanmay shape-shifts into a Small swan, or it returns to its true humanoid form. Its game statistics are the same in each form, except where noted. Any equipment it is wearing or carrying isn't transformed.


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