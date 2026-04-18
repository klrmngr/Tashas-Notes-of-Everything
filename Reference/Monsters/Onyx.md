---
type: pc
race: "Creature"
class:
 - "Onyx"
subClass:
 - "CR —"
cover: "Onyx.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/huge
  - cr/—
  - source/oow
---
###### Onyx
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: OoW
___

> [!infobox|no-t right]
> ![[Onyx.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Huge Creature |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | — |
> | :FasHeart: HP | — |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | OoW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 400 ft., climb 200 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Actions

**Claws.** Melee Weapon Attack: +7 to hit, reach 20 ft., one target. *Hit:* 11 (2d10) slashing damage.


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