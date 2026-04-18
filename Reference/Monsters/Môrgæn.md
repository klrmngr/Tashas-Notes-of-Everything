---
type: pc
race: "Humanoid (elf)"
class:
 - "Môrgæn"
subClass:
 - "CR 4"
cover: "Môrgæn.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/ai
---
###### Môrgæn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Môrgæn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (studded leather) |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 12 | 12 | 14 | 10 |
| **Mod** | +1 | +4 | +1 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Draconic, Dwarvish, Giant, Goblin
**Saving Throws:** Str +3, Dex +6
**Skills:** Athletics +3, Insight +4, Nature +3, Perception +4, Stealth +6, Survival +4

---

### Traits

**Fey Ancestry.** Môrgæn has advantage on saving throws against being charmed, and magic can't put her to sleep.


---

### Actions

**Multiattack.** Môrgæn makes three attacks with her scimitars or her longbow.

**Scimitars.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Longbow.** Ranged Weapon Attack: +6 to hit, range 150/600 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage.


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