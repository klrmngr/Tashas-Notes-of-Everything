---
type: pc
race: "Humanoid (leonin)"
class:
 - "Leonin Iconoclast"
subClass:
 - "CR 5"
cover: "Leonin Iconoclast.png"
campaign:
locations:
tags:
  - race/leonin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/mot
---
###### Leonin Iconoclast
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Leonin Iconoclast.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (leonin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (Unarmored Defense) |
> | :FasHeart: HP | 67 (9d8 + 27) |
> | :FasUserGroup: Race | Humanoid (leonin) |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 16 | 13 | 17 | 10 |
| **Mod** | +2 | +4 | +3 | +1 | +3 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Leonin
**Saving Throws:** Dex +7, Wis +6
**Skills:** Arcana +4, Insight +6, Intimidation +3, Stealth +7, Survival +6

---

### Traits

**Evasion.** If the leonin is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails. It can't use this trait if it's incapacitated.

**Unarmored Defense.** While the leonin is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The leonin makes three weapon attacks.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) slashing damage plus 7 (2d6) force damage.

**Dart.** Ranged Weapon Attack: +7 to hit, range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.


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