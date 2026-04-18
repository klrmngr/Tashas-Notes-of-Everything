---
type: pc
race: "Humanoid"
class:
 - "Cultist of Myrkul"
subClass:
 - "CR 11"
cover: "Cultist of Myrkul.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/11
  - source/fraif
---
###### Cultist of Myrkul
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Cultist of Myrkul.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 204 (24d8 + 96) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 14 | 18 | 20 | 18 | 15 |
| **Mod** | +1 | +2 | +4 | +5 | +4 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 14
**Languages:** Common
**Saving Throws:** Con +8, Int +9, Wis +8, Cha +6
**Skills:** Arcana +9, Insight +8, Religion +9
**Damage Resistances:** necrotic

---

### Traits

**Nearer to the Dead.** While Bloodied, the cultist has Immunity to the Frightened and Poisoned conditions.


---

### Actions

**Multiattack.** The cultist makes three Necrotic Burst attacks.

**Necrotic Burst.** m,r +9, reach 5 ft. or range 120 ft. *Hit:* 27 (5d10) Necrotic damage and the target can't regain Hit Points until the end of the cultist's next turn.


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