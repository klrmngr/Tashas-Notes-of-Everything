---
type: pc
race: "Humanoid (elf)"
class:
 - "Yinra Emberwind"
subClass:
 - "CR 1/2"
cover: "Yinra Emberwind.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/egw
---
###### Yinra Emberwind
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Yinra Emberwind.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 12 | 14 | 13 | 11 |
| **Mod** | +0 | +3 | +1 | +2 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish
**Skills:** Investigation +4, Perception +3, Stealth +5

---

### Traits

**Fey Ancestry.** Yinra has advantage on saving throws against being charmed, and magic can't put her to sleep.

**Keen Hearing and Sight.** Yinra has advantage on Wisdom (Perception) checks that rely on hearing or sight.


---

### Actions

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Longbow.** Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.


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