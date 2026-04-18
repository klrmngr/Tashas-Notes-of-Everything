---
type: pc
race: "Fey"
class:
 - "Faerie Borrower"
subClass:
 - "CR 1/2"
cover: "Faerie Borrower.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1-2
  - source/mcv4ec
---
###### Faerie Borrower
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Faerie Borrower.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 12 (5d4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 20 | 10 | 13 | 12 | 16 |
| **Mod** | -4 | +5 | +0 | +1 | +1 | +3 |

**Speed:** 10 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Sylvan
**Skills:** Sleight Of Hand +7, Stealth +7

---

### Traits

**Flyby.** The faerie doesn't provoke opportunity attacks when it flies out of an enemy's reach.


---

### Actions

**Needle Blade.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d4 + 5) piercing damage.

**Magic Mockery.** The faerie hurls magical taunts at one creature it can see within 60 feet of itself. The creature must succeed on a DC 13 Wisdom saving throw or take 3 (1d6) psychic damage and have disadvantage on attack rolls and ability checks until the start of the faerie's next turn.


---

### Reactions

**Tricksy Parry.** Immediately after taking damage, the faerie reduces the damage taken by 2 (1d4).


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