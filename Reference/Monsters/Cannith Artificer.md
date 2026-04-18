---
type: pc
race: "Humanoid (human)"
class:
 - "Cannith Artificer"
subClass:
 - "CR 4"
cover: "Cannith Artificer.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/efa
---
###### Cannith Artificer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Cannith Artificer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (human) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 13 | 14 | 18 | 14 | 11 |
| **Mod** | +1 | +1 | +2 | +4 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common plus two other languages
**Saving Throws:** Con +4, Int +6
**Skills:** Arcana +6, Perception +4, Sleight Of Hand +3

---

### Actions

**Multiattack.** The artificer makes two attacks, using Battering Mace or Artillery Strike in any combination.

**Battering Mace.** m +6, reach 5 ft. *Hit:* 14 (3d6 + 4) Bludgeoning damage, and if the target is a Large or smaller creature, it has the Prone condition.

**Artillery Strike.** r +6, range 120 ft. *Hit:* 22 (4d8 + 4) Force damage.


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