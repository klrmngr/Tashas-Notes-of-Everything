---
type: pc
race: "Humanoid (wizard)"
class:
 - "Quandrix Pledgemage"
subClass:
 - "CR 4"
cover: "Quandrix Pledgemage.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/scc
---
###### Quandrix Pledgemage
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Quandrix Pledgemage.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 13 | 17 | 14 | 11 |
| **Mod** | +0 | +2 | +1 | +3 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus any two languages
**Saving Throws:** Int +5, Wis +4
**Skills:** Arcana +7, Investigation +7, Nature +5

---

### Actions

**Multiattack.** The pledgemage makes two Exponential Lash attacks.

**Exponential Lash.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 6 (1d6 + 3) force damage, and the pledgemage can cause one creature it can see within 30 feet of the target to take 10 (2d6 + 3) force damage.


---

### Bonus Actions

**Vortex Calculus (Recharge 4–6).** The pledgemage teleports, along with any equipment it is wearing or carrying, to an unoccupied space it can see within 60 feet of itself. Immediately after it teleports, each creature within 20 feet of the space it left must make a DC 13 Constitution saving throw. On a failed save, a creature takes 7 (2d6) force damage and is moved 10 feet in a random horizontal direction. On a successful save, a creature takes half as much damage and isn't moved.


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