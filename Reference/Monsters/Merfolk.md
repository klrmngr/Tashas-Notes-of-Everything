---
type: pc
race: "Humanoid (merfolk)"
class:
 - "Merfolk"
subClass:
 - "CR 1/8"
cover: "Merfolk.png"
campaign:
locations:
tags:
  - race/merfolk
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/mm
---
###### Merfolk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Merfolk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid (merfolk) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (merfolk) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 12 | 11 | 11 | 12 |
| **Mod** | +0 | +1 | +1 | +0 | +0 | +1 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Aquan, Common
**Skills:** Perception +2

---

### Traits

**Amphibious.** The merfolk can breathe air and water.


---

### Actions

**Spear.** Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 3 (1d6) piercing damage, or 4 (1d8) piercing damage if used with two hands to make a melee attack.


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