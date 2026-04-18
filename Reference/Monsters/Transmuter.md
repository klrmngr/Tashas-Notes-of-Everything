---
type: pc
race: "Humanoid (any race)"
class:
 - "Transmuter"
subClass:
 - "CR 5"
cover: "Transmuter.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/vgm
---
###### Transmuter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Transmuter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 11 | 17 | 12 | 11 |
| **Mod** | -1 | +2 | +0 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** any four languages
**Saving Throws:** Int +6, Wis +4
**Skills:** Arcana +6, History +6

---

### Traits

**Transmuter's Stone.** The transmuter carries a magic stone it crafted that grants its bearer one of the following effects:
Darkvision out to a range of 60 feet
An extra 10 feet of speed while the bearer is unencumbered
Proficiency with Constitution saving throws
Resistance to acid, cold, fire, lightning, or thunder damage (transmuter's choice whenever the transmuter chooses this benefit)
If the transmuter has the stone and casts a transmutation spell of 1st level or higher, it can change the effect of the stone.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d6 - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two hands.


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