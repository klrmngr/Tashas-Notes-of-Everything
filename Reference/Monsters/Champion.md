---
type: pc
race: "Humanoid"
class:
 - "Champion"
subClass:
 - "CR 9"
cover: "Champion.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/mpmm
---
###### Champion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Champion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 143 (22d8 + 44) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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


---

### Actions

**Multiattack.** The champion makes three Greatsword or Shortbow attacks.

**Greatsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage, plus 7 (2d6) slashing damage if the champion has more than half of its total hit points remaining.

**Shortbow.** Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, plus 7 (2d6) piercing damage if the champion has more than half of its total hit points remaining.


---

### Bonus Actions

**Second Wind (Recharges after a Short or Long Rest).** The champion regains 20 hit points.


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