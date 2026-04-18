---
type: pc
race: "Humanoid"
class:
 - "Champion of Gorm"
subClass:
 - "CR 2"
cover: "Champion of Gorm.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/qftis
---
###### Champion of Gorm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Champion of Gorm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 19 (splint armor, shield) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 12 | 12 | 15 | 16 |
| **Mod** | +3 | +0 | +1 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Saving Throws:** Str +5, Wis +4
**Skills:** Athletics +5, Insight +4, Religion +3

---

### Traits

**Brave.** The champion has advantage on saving throws against the frightened condition.


---

### Actions

**Multiattack.** The champion makes two Lightning Mace attacks or three Handaxe attacks.

**Lightning Mace.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 5 (2d4) lightning damage.

**Handaxe.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


---

### Bonus Actions

**Aura of Resilience (1/Day).** The champion exudes an aura of ghostly lightning that fills a 10-foot-radius sphere centered on itself. While this aura is active, the champion and each creature of its choice within the aura have advantage on saving throws. The aura moves with the champion and lasts for 1 minute, until the champion has the incapacitated condition, or until the champion uses another bonus action to end the aura.


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