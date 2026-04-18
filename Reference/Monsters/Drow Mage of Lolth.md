---
type: pc
race: "Humanoid (elf)"
class:
 - "Drow Mage of Lolth"
subClass:
 - "CR 7"
cover: "Drow Mage of Lolth.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/fraif
---
###### Drow Mage of Lolth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Drow Mage of Lolth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 81 (18d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 10 | 17 | 13 | 12 |
| **Mod** | -1 | +2 | +0 | +3 | +1 | +1 |

**Speed:** 30 ft., fly 15 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 14
**Languages:** Abyssal, Common, Elvish, Undercommon
**Saving Throws:** Dex +5, Wis +4
**Skills:** Arcana +6, Perception +4, Stealth +5

---

### Traits

**Fey Ancestry.** The drow has Advantage on saving throws it makes to avoid or end the Charmed condition, and magic can't put the drow to sleep.

**Sunlight Sensitivity.** While in sunlight, the drow has Disadvantage on attack rolls.


---

### Actions

**Multiattack.** The drow makes three Abyssal Burst attacks.

**Abyssal Burst.** m,r +6, reach 5 ft. or range 120 ft. *Hit:* 21 (4d8 + 3) Poison damage.


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