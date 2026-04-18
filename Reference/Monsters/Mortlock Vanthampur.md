---
type: pc
race: "Humanoid (human)"
class:
 - "Mortlock Vanthampur"
subClass:
 - "CR 3"
cover: "Mortlock Vanthampur.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/bgdia
---
###### Mortlock Vanthampur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Mortlock Vanthampur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 90 (12d8 + 36) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 17 | 10 | 12 | 13 |
| **Mod** | +4 | +2 | +3 | +0 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common
**Skills:** Athletics +6, Intimidation +5

---

### Traits

**Indomitable (2/Day).** Mortlock can reroll a saving throw that he fails. He must use the new roll.


---

### Actions

**Multiattack.** Mortlock makes two attacks with his greatclub.

**Greatclub.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage, plus 5 (2d4) bludgeoning damage if Mortlock has taken any damage since his last turn.

**Heavy Crossbow.** Ranged Weapon Attack: +4 to hit, range 100/400 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.


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