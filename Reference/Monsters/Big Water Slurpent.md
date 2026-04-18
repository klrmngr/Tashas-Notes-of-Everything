---
type: pc
race: "Elemental"
class:
 - "Big Water Slurpent"
subClass:
 - "CR 3"
cover: "Big Water Slurpent.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/3
  - source/awm
---
###### Big Water Slurpent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Big Water Slurpent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 58 |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 13 | 11 | 10 | 10 |
| **Mod** | +3 | +3 | +1 | +0 | +0 | +0 |

**Speed:** 0 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Invisible in Water.** The big water slurpent is invisible while fully immersed in water.

**Water Bound.** The big water slurpent dies if it leaves the water to which it is bound or if that water is destroyed.


---

### Actions

**Constrict.** Melee Weapon Attack: +5 to hit, one target. *Hit:* 13 (3d6+3) bludgeoning damage. If the target is Medium or smaller, it is grappled (escape DC 13) and pulled 5 feet toward the big water slurpent. Until this grapple ends, the target is restrained, the big water slurpent tries to drown it, and the big water slurpent can't constrict another target.


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