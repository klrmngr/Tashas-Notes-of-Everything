---
type: pc
race: "Creature"
class:
 - "Infant Basilisk"
subClass:
 - "CR 0"
cover: "Infant Basilisk.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/tiny
  - cr/0
  - source/oota
---
###### Infant Basilisk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Infant Basilisk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Creature |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 4 (1d4 + 2) |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Actions

**Bite.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 1 piercing damage plus 1 poison damage.


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