---
type: pc
race: "Humanoid (elf)"
class:
 - "Vulkoori Stingblade"
subClass:
 - "CR 1/2"
cover: "Vulkoori Stingblade.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/efa
---
###### Vulkoori Stingblade
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Vulkoori Stingblade.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 27 (6d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 10 | 11 | 12 | 12 |
| **Mod** | +0 | +2 | +0 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 13
**Languages:** Common, Elvish, Giant
**Saving Throws:** Dex +4
**Skills:** Perception +3, Stealth +4
**Damage Resistances:** poison

---

### Traits

**Fey Ancestry.** Magic can't put the stingblade to sleep.


---

### Actions

**Stingblade.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 2 (1d4) Poison damage.

**Boomerang.** r +4, reach 30/120 ft. *Hit:* 7 (2d4 + 2) Bludgeoning damage.


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