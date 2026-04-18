---
type: pc
race: "Fiend (demon)"
class:
 - "Manes"
subClass:
 - "CR 1/8"
cover: "Manes.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/small
  - cr/1-8
  - source/xmm
---
###### Manes
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Manes.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Fiend (demon) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 9 (2d6 + 2) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 9 | 13 | 3 | 8 | 4 |
| **Mod** | +0 | -1 | +1 | -4 | -1 | -3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 9
**Languages:** understands Abyssal but can't speak
**Damage Resistances:** cold; fire; lightning
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Actions

**Claw.** m +2, reach 5 ft. *Hit:* 5 (2d4) Slashing damage.


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