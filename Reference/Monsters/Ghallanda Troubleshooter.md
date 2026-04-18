---
type: pc
race: "Humanoid (halfling)"
class:
 - "Ghallanda Troubleshooter"
subClass:
 - "CR 3"
cover: "Ghallanda Troubleshooter.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/efa
---
###### Ghallanda Troubleshooter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Ghallanda Troubleshooter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 78 (12d6 + 36) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 17 | 13 | 14 | 17 |
| **Mod** | +0 | +3 | +3 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Halfling
**Saving Throws:** Dex +5, Con +5, Wis +4, Cha +5
**Skills:** Insight +4, Perception +4, Stealth +5
**Condition Immunities:** frightened

---

### Traits

**Hustle.** The troubleshooter can move through the space of any creature that is of a larger size, but it can't stop there.


---

### Actions

**Multiattack.** The troubleshooter makes two Poisoned Dagger attacks.

**Poisoned Dagger.** m,r +5, reach 5 ft. or range 20/60 ft. *Hit:* 5 (1d4 + 3) Piercing damage, and the target has the Poisoned condition until the start of the troubleshooter's next turn.


---

### Bonus Actions

**Nimble Escape.** The troubleshooter takes the Disengage or Hide action.


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