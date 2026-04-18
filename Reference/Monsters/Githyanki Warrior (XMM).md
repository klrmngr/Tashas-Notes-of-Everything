---
type: pc
race: "Aberration (gith)"
class:
 - "Githyanki Warrior"
subClass:
 - "CR 3"
cover: "Githyanki Warrior.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/3
  - source/xmm
---
###### Githyanki Warrior
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Githyanki Warrior.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Aberration (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Aberration (gith) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 12 | 13 | 13 | 10 |
| **Mod** | +2 | +2 | +1 | +1 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Gith
**Saving Throws:** Con +3, Int +3, Wis +3

---

### Actions

**Multiattack.** The githyanki makes two Psi Blade attacks.

**Psi Blade.** m +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Slashing damage plus 7 (2d6) Psychic damage.


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