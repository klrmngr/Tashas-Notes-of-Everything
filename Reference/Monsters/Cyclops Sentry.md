---
type: pc
race: "Giant"
class:
 - "Cyclops Sentry"
subClass:
 - "CR 6"
cover: "Cyclops Sentry.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/6
  - source/xmm
---
###### Cyclops Sentry
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Cyclops Sentry.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 11 | 20 | 8 | 6 | 10 |
| **Mod** | +6 | +0 | +5 | -1 | -2 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 8
**Languages:** Giant

---

### Actions

**Multiattack.** The cyclops makes two attacks, using Stone Club or Rock in any combination.

**Stone Club.** m +9, reach 10 ft. *Hit:* 16 (3d6 + 6) Bludgeoning damage. If the target is a Huge or smaller creature, it has the Prone condition.

**Rock.** r +9, range 30/120 ft. *Hit:* 22 (3d10 + 6) Bludgeoning damage.


---

### Reactions

**Limited Foresight (Recharge 6).**  A creature the cyclops can see makes an attack roll against it.  The cyclops imposes Disadvantage on the roll, and the cyclops gains Advantage on attack rolls against the target until the end of the cyclops's next turn.


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