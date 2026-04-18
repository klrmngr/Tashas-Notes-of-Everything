---
type: pc
race: "Humanoid"
class:
 - "Tough Boss"
subClass:
 - "CR 4"
cover: "Tough Boss.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/xmm
---
###### Tough Boss
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Tough Boss.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 16 | 11 | 10 | 11 |
| **Mod** | +3 | +2 | +3 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common plus one other language
**Saving Throws:** Str +5, Con +5, Cha +2

---

### Traits

**Pack Tactics.** The tough has Advantage on an attack roll against a creature if at least one of the tough's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Multiattack.** The tough makes two attacks, using Warhammer or Heavy Crossbow in any combination.

**Warhammer.** m +5, reach 5 ft. *Hit:* 12 (2d8 + 3) Bludgeoning damage. If the target is a Large or smaller creature, the tough pushes the target up to 10 feet straight away from itself.

**Heavy Crossbow.** r +4, range 100/400 ft. *Hit:* 13 (2d10 + 2) Piercing damage.


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