---
type: pc
race: "Humanoid (human)"
class:
 - "Sentinel Marshal"
subClass:
 - "CR 6"
cover: "Sentinel Marshal.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/6
  - source/efa
---
###### Sentinel Marshal
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Sentinel Marshal.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Small Humanoid (human) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 110 (20d8 + 20) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 19 | 12 | 11 | 15 | 10 |
| **Mod** | +4 | +4 | +1 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Common plus two other languages
**Saving Throws:** Dex +7, Con +4
**Skills:** Athletics +7, Insight +5, Perception +8

---

### Actions

**Multiattack.** The marshal makes three attacks, using Longsword or Pistol in any combination.

**Longsword.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Slashing damage, and the target has Disadvantage on the next attack roll it makes before the start of the marshal's next turn.

**Pistol.** r +7, range 30/90 ft. *Hit:* 15 (2d10 + 4) Piercing damage.


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