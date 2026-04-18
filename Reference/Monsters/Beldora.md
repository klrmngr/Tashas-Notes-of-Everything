---
type: pc
race: "Humanoid (human)"
class:
 - "Beldora"
subClass:
 - "CR —"
cover: "Beldora.png"
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
###### Beldora
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Beldora.png]]
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
| **Score** | 10 | 14 | 10 | 16 | 12 | 16 |
| **Mod** | +0 | +2 | +0 | +3 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Draconic, Dwarvish, Halfling
**Skills:** Deception +5, Insight +3, Investigation +5, Perception +5, Persuasion +5

---

### Traits

**Roleplaying Information.** Beldora is a member of the harpers who survives using her wits and wiles. She looks like a homeless waif, but she's a survivor who shies away from material wealth.
Ideal: "We should all strive to help one another"
Bond: "I'll risk my life to protect the powerless."
Flaw: "I like lying to people. Makes life more interesting, no?"


---

### Actions

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Hand Crossbow.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage. Beldora carries ten crossbow bolts.


---

### Reactions

**Duck and Cover.** Beldora adds 2 to her AC against one ranged attack that would hit her. To do so, Beldora must see the attacker and can't be grappled or restrained.


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