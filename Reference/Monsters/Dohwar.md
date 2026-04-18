---
type: pc
race: "Fey"
class:
 - "Dohwar"
subClass:
 - "CR 0"
cover: "Dohwar.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/0
  - source/bam
---
###### Dohwar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Dohwar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 10 (3d6) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 5 | 12 | 11 | 11 | 14 | 13 |
| **Mod** | -3 | +1 | +0 | +0 | +2 | +1 |

**Speed:** 20 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Dohwar, telepathy 30 ft. (see also Merging below)
**Saving Throws:** Dex +3, Wis +4
**Skills:** Deception +3, Insight +4, Persuasion +3

---

### Traits

**Merging.** Two dohwars can have a telepathic conversation with each other and a third willing creature of their choice, provided all three are within 30 feet of one another.


---

### Actions

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.


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