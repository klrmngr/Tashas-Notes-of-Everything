---
type: pc
race: "Monstrosity"
class:
 - "Bulette Pup"
subClass:
 - "CR 2"
cover: "Bulette Pup.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/xmm
---
###### Bulette Pup
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bulette Pup.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 8 | 17 | 2 | 10 | 4 |
| **Mod** | +3 | -1 | +3 | -4 | +0 | -3 |

**Speed:** 30 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 30 ft., Tremorsense 60 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4

---

### Actions

**Bite.** m +5, reach 5 ft. *Hit:* 14 (2d10 + 3) Piercing damage.


---

### Bonus Actions

**Leap.** The bulette jumps up to 30 feet by spending 10 feet of movement.


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