---
type: pc
race: "Fiend"
class:
 - "Gnoll Fang of Yeenoghu"
subClass:
 - "CR 4"
cover: "Gnoll Fang of Yeenoghu.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/xmm
---
###### Gnoll Fang of Yeenoghu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gnoll Fang of Yeenoghu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 15 | 10 | 11 | 13 |
| **Mod** | +3 | +2 | +2 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Abyssal, Gnoll
**Saving Throws:** Con +4, Wis +2, Cha +3

---

### Actions

**Multiattack.** The gnoll makes one Bite attack and two Bone Flail attacks.

**Bite.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing damage plus 7 (2d6) Poison damage, and the target has the Poisoned condition until the start of the gnoll's next turn.

**Bone Flail.** m +5, reach 10 ft. *Hit:* 7 (1d8 + 3) Piercing damage.


---

### Bonus Actions

**Rampage (2/Day).** Immediately after dealing damage to a creature that is already Bloodied, the gnoll moves up to half its Speed, and it makes one Bite attack.


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