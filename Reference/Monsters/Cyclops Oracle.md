---
type: pc
race: "Giant"
class:
 - "Cyclops Oracle"
subClass:
 - "CR 10"
cover: "Cyclops Oracle.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/10
  - source/xmm
---
###### Cyclops Oracle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Cyclops Oracle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 207 (18d12 + 90) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 11 | 20 | 16 | 18 | 10 |
| **Mod** | +6 | +0 | +5 | +3 | +4 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Truesight 30 ft., passive Perception 22
**Languages:** Giant
**Saving Throws:** Con +9, Wis +8
**Skills:** History +11, Perception +12

---

### Actions

**Multiattack.** The cyclops makes three attacks, using Radiant Strike or Flash of Light in any combination.

**Radiant Strike.** m +10, reach 10 ft. *Hit:* 22 (3d10 + 6) Radiant damage.

**Flash of Light.** r +10, range 120 ft. *Hit:* 17 (2d10 + 6) Radiant damage, and the target has Disadvantage on attack rolls until the end of the cyclops's next turn.


---

### Reactions

**Portent (Recharge 4–6).**  The cyclops or an ally it can see makes a D20 Test.  The cyclops rolls 1d20 and chooses whether to use that roll in place of the d20 rolled for the D20 Test.


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