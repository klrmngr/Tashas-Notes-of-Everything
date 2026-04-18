---
type: pc
race: "Humanoid"
class:
 - "Transmuter Wizard"
subClass:
 - "CR 5"
cover: "Transmuter Wizard.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/mpmm
---
###### Transmuter Wizard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Transmuter Wizard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 49 (11d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Transmuter's Stone.** The transmuter carries a magic stone it crafted. The stone grants it one of the following benefits while bearing the stone; the transmuter chooses the benefit at the end of each long rest:
- **Darkvision.** The transmuter has darkvision out to a range of 60 feet.
- **Resilience.** The transmuter has proficiency in Constitution saving throws. 
- **Resistance.** The transmuter has resistance to acid, cold, fire, lightning, or thunder damage (transmuter's choice whenever choosing this benefit).
- **Speed.** The transmuter's walking speed is increased by 10 feet.


---

### Actions

**Multiattack.** The transmuter makes three Arcane Burst attacks.

**Arcane Burst.** Melee or Ranged Spell Attack: +6 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 19 (3d10 + 3) acid damage.


---

### Bonus Actions

**Transmute (Recharge 4–6).** The transmuter casts alter self or changes the benefit of Transmuter's Stone if bearing the stone.


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