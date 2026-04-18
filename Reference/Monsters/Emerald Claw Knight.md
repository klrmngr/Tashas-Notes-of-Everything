---
type: pc
race: "Humanoid"
class:
 - "Emerald Claw Knight"
subClass:
 - "CR 2"
cover: "Emerald Claw Knight.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/efa
---
###### Emerald Claw Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Emerald Claw Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 11 | 14 | 13 | 10 | 13 |
| **Mod** | +3 | +0 | +2 | +1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Dwarvish
**Saving Throws:** Wis +2
**Skills:** Athletics +5, Perception +2

---

### Actions

**Multiattack.** The knight makes two attacks, using Flail or Javelin in any combination.

**Flail.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning damage—plus 4 (1d8) Necrotic damage if the knight is Bloodied—and the target has Disadvantage on its next attack roll before the start of the knight's next turn.

**Javelin.** m,r +5, reach 5 ft. or range 30/120 ft. *Hit:* 6 (1d6 + 3) Piercing damage—plus 4 (1d8) Necrotic damage if the knight is Bloodied.


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