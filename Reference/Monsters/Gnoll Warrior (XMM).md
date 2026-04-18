---
type: pc
race: "Fiend"
class:
 - "Gnoll Warrior"
subClass:
 - "CR 1/2"
cover: "Gnoll Warrior.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/1-2
  - source/xmm
---
###### Gnoll Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gnoll Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 11 | 6 | 10 | 7 |
| **Mod** | +2 | +1 | +0 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Gnoll

---

### Actions

**Rend.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage.

**Bone Bow.** r +3, range 150/600 ft. *Hit:* 6 (1d10 + 1) Piercing damage.


---

### Bonus Actions

**Rampage (1/Day).** Immediately after dealing damage to a creature that is already Bloodied, the gnoll moves up to half its Speed, and it makes one Rend attack.


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