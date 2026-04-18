---
type: pc
race: "Humanoid (human)"
class:
 - "Narth Tezrin"
subClass:
 - "CR —"
cover: "Narth Tezrin.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/skt
---
###### Narth Tezrin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Narth Tezrin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 18 (4d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 10 | 12 | 14 | 16 |
| **Mod** | +0 | +2 | +0 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Dwarvish
**Skills:** Insight +4, Investigation +3, Perception +6, Persuasion +5

---

### Traits

**Cunning Action.** On each of his turns, Narth can use a bonus action to take the Dash, Disengage, or Hide action.

**Roleplaying Information.** Narth sells gear to adventurers, and he also has an adventurous spirit. The Lionshield Coster pays him well, but he longs to make a name for himself. At the same time, he runs a business with his partner Alaestra and knows she wouldn't forgive him if he ran off and never returned.
Ideal: "The bigger the risk, the greater the reward."
Bond: "I adore my colleague Alestra, and I'd like to do something to impress her."
Flaw: "I'll risk life and limb to become a legend.-"


---

### Actions

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Hand Crossbow.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage. Narth carries twenty crossbow bolts.


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