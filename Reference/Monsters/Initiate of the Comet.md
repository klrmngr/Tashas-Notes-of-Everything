---
type: pc
race: "Humanoid (warlock)"
class:
 - "Initiate of the Comet"
subClass:
 - "CR 4"
cover: "Initiate of the Comet.png"
campaign:
locations:
tags:
  - race/warlock
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/bmt
---
###### Initiate of the Comet
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Initiate of the Comet.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (warlock) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Humanoid (warlock) |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 16 | 11 | 13 | 17 |
| **Mod** | +1 | +2 | +3 | +0 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any one language
**Saving Throws:** Wis +3, Cha +5
**Skills:** Arcana +2

---

### Traits

**Magic Resistance.** The initiate has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The initiate makes two Comet Strike attacks.

**Comet Strike.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 14 (2d10 + 3) force damage.


---

### Reactions

**Moment of Foresight (1/Day).** When hit by an attack roll, the initiate can force the attacker to reroll it and use the new roll, possibly causing the attack to miss.


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