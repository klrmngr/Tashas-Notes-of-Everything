---
type: pc
race: "Humanoid (human)"
class:
 - "Falcon the Hunter"
subClass:
 - "CR 4"
cover: "Falcon the Hunter.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/dip
---
###### Falcon the Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DIP
___

> [!infobox|no-t right]
> ![[Falcon the Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 14 (studded leather) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | DIP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 16 | 11 | 16 | 15 |
| **Mod** | +2 | +2 | +3 | +0 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common
**Saving Throws:** Dex +4, Wis +5
**Skills:** Athletics +4, Perception +7, Survival +5

---

### Traits

**Archer.** A longbow or shortbow deals one extra die of its damage when Falcon hits with it (included in his longbow attack).

**Sharpshooter.** Falcon's ranged weapon attacks ignore 3 and 3.


---

### Actions

**Multiattack.** Falcon makes three melee attacks or two ranged attacks.

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.


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