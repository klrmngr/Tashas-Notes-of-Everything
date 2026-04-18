---
type: pc
race: "Humanoid (gith)"
class:
 - "Githzerai Monk"
subClass:
 - "CR 2"
cover: "Githzerai Monk.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mm
---
###### Githzerai Monk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Githzerai Monk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 38 (7d8 + 7) |
> | :FasUserGroup: Race | Humanoid (gith) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 12 | 13 | 14 | 10 |
| **Mod** | +1 | +2 | +1 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Gith
**Saving Throws:** Str +3, Dex +4, Int +3, Wis +4
**Skills:** Insight +4, Perception +4

---

### Traits

**Psychic Defense.** While the githzerai is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The githzerai makes two unarmed strikes.

**Unarmed Strike.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage plus 9 (2d8) psychic damage. This is a magic weapon attack.


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