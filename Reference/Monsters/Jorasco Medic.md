---
type: pc
race: "Humanoid (halfling)"
class:
 - "Jorasco Medic"
subClass:
 - "CR 4"
cover: "Jorasco Medic.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/efa
---
###### Jorasco Medic
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Jorasco Medic.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 58 (9d6 + 27) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 16 | 14 | 17 | 14 |
| **Mod** | +1 | +2 | +3 | +2 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Halfling
**Saving Throws:** Con +5, Wis +5
**Skills:** Insight +5, Medicine +5, Perception +5, Stealth +4

---

### Traits

**Lucky.** When the medic rolls a 1 on the d20 of a D20 Test, it can reroll the die, and it must use the new roll.


---

### Actions

**Multiattack.** The medic makes two Radiant Burst attacks.

**Radiant Burst.** m,r +5, reach 5 ft. or range 30 ft. *Hit:* 7 (2d6) Radiant damage, and the creature has the Blinded condition until the start of the medic's next turn.


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