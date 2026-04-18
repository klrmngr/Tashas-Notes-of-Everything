---
type: pc
race: "Humanoid"
class:
 - "Champion of Madarua"
subClass:
 - "CR 2"
cover: "Champion of Madarua.png"
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
###### Champion of Madarua
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Champion of Madarua.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 15 | 12 | 12 | 14 |
| **Mod** | +3 | +1 | +2 | +1 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common
**Saving Throws:** Str +5, Dex +3
**Skills:** Acrobatics +3, Religion +3

---

### Actions

**Multiattack.** The champion makes three Longsword attacks.

**Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage, or 8 (1d10 + 3) piercing damage if used with two hands.


---

### Bonus Actions

**Aura of Fury (1/Day).** The champion summons an aura of ghostly animals that fills a 10-foot-radius sphere centered on itself. While this aura is active, the champion and all its allies in the aura have advantage on attack rolls. The aura moves with the champion and lasts for 1 minute, until the champion has the incapacitated condition, or until the champion uses another bonus action to end the aura.


---

### Reactions

**Parry.** The champion adds 2 to its AC against one melee attack that would hit it. To do so, the champion must see the attacker and be wielding a melee weapon.


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