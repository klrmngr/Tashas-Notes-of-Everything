---
type: pc
race: "Humanoid (locathah)"
class:
 - "Locathah"
subClass:
 - "CR 1/2"
cover: "Locathah.png"
campaign:
locations:
tags:
  - race/locathah
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/gos
---
###### Locathah
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Locathah.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (locathah) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (locathah) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 12 | 12 | 11 | 10 | 11 |
| **Mod** | +1 | +1 | +1 | +0 | +0 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Aquan, Common
**Saving Throws:** Dex +3
**Skills:** Athletics +3, Perception +2

---

### Traits

**Leviathan Will.** The locathah has advantage on saving throws against being charmed, frightened, paralyzed, poisoned, stunned, or put to sleep.

**Limited Amphibiousness.** The locathah can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.


---

### Actions

**Multiattack.** The locathah makes two melee attacks with its spear.

**Spear.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage, or 5 (1d8 + 1) piercing damage if used with two hands.


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