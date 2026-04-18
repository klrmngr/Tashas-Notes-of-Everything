---
type: pc
race: "Humanoid (sahuagin)"
class:
 - "Sahuagin High Priestess"
subClass:
 - "CR 5"
cover: "Sahuagin High Priestess.png"
campaign:
locations:
tags:
  - race/sahuagin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/gos
---
###### Sahuagin High Priestess
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Sahuagin High Priestess.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (sahuagin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Humanoid (sahuagin) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 14 | 12 | 16 | 10 |
| **Mod** | +2 | +1 | +2 | +1 | +3 | +0 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Sahuagin
**Saving Throws:** Wis +6
**Skills:** Insight +6, Perception +6

---

### Traits

**Blood Frenzy.** The high priestess has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Limited Amphibiousness.** The high priestess can breathe air and water, but she needs to be submerged at least once every 4 hours to avoid suffocating.

**Shark Telepathy.** The high priestess can magically command any shark within 120 feet of her, using a limited telepathy.


---

### Actions

**Multiattack.** The high priestess makes two attacks with her toothsome staff, or one attack with her bite and one with her claws.

**Toothsome Staff.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.


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