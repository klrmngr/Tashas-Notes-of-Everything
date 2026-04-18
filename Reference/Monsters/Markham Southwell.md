---
type: pc
race: "Humanoid (human)"
class:
 - "Markham Southwell"
subClass:
 - "CR —"
cover: "Markham Southwell.png"
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
###### Markham Southwell
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Markham Southwell.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 (splint armor) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 13 | 14 | 11 | 16 | 14 |
| **Mod** | +2 | +1 | +2 | +0 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common
**Skills:** Perception +5, Survival +5

---

### Traits

**Roleplaying Information.** Sheriff Markham of Bryn Shander is a brawny, likable man of few words. Nothing is more important to him than protecting Icewind Dale. He judges others by their actions, not their words.
Ideal: "All people deserve to be treated with dignity."
Bond: "Duvessa is a natural leader, but she needs help. That's my job."
Flaw: "I bury my emotions and have no interest in small talk."


---

### Actions

**Multiattack.** Markham makes two melee attacks.

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands.

**Heavy Crossbow.** Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. *Hit:* 6 (1d10 + 1) piercing damage. Markham carries twenty crossbow bolts.


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