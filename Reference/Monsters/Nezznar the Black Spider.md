---
type: pc
race: "Humanoid (elf)"
class:
 - "Nezznar the Black Spider"
subClass:
 - "CR 2"
cover: "Nezznar the Black Spider.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/lmop
---
###### Nezznar the Black Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Lost Mine of Phandelver
___

> [!infobox|no-t right]
> ![[Nezznar the Black Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11; 14 with mage armor |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Lost Mine of Phandelver |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 13 | 10 | 16 | 14 | 13 |
| **Mod** | -1 | +1 | +0 | +3 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** Elvish, Undercommon
**Saving Throws:** Int +5, Wis +4
**Skills:** Arcana +5, Perception +4, Stealth +3

---

### Traits

**Special Equipment.** Nezznar has a spider staff.

**Fey Ancestry.** Nezznar has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Sunlight Sensitivity.** Nezznar has disadvantage on attack rolls when he or his target is in sunlight.


---

### Actions

**Spider Staff.** Melee Weapon Attack: +1 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) bludgeoning damage plus 3 (1d6) poison damage.


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