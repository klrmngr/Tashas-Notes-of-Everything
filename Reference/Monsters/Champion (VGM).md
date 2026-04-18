---
type: pc
race: "Humanoid (any race)"
class:
 - "Champion"
subClass:
 - "CR 9"
cover: "Champion.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/vgm
---
###### Champion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Champion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 14 | 10 | 14 | 12 |
| **Mod** | +5 | +2 | +2 | +0 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** any one language (usually Common)
**Saving Throws:** Str +9, Con +6
**Skills:** Athletics +9, Intimidation +5, Perception +6

---

### Traits

**Indomitable (2/Day).** The champion rerolls a failed saving throw.

**Second Wind (Recharges after a Short or Long Rest).** As a bonus action, the champion can regain 20 hit points.


---

### Actions

**Multiattack.** The champion makes three attacks with its greatsword or its shortbow.

**Greatsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage, plus 7 (2d6) slashing damage if the champion has more than half of its total hit points remaining.

**Shortbow.** Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, plus 7 (2d6) piercing damage if the champion has more than half of its total hit points remaining.


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