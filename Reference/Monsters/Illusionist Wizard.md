---
type: pc
race: "Humanoid"
class:
 - "Illusionist Wizard"
subClass:
 - "CR 3"
cover: "Illusionist Wizard.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/mpmm
---
###### Illusionist Wizard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Illusionist Wizard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 14 | 13 | 16 | 11 | 12 |
| **Mod** | -1 | +2 | +1 | +3 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** any four languages
**Saving Throws:** Int +5, Wis +2
**Skills:** Arcana +5, History +5

---

### Actions

**Multiattack.** The illusionist makes two Arcane Burst attacks.

**Arcane Burst.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 14 (2d10 + 3) psychic damage.


---

### Bonus Actions

**Displacement (Recharge 5–6).** The illusionist projects an illusion that makes the illusionist appear to be standing in a place a few inches from its actual location, causing any creature to have disadvantage on attack rolls against the illusionist. The effect lasts for 1 minute, and it ends early if the illusionist takes damage, if it is incapacitated, or if its speed becomes 0.


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