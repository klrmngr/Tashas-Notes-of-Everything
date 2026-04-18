---
type: pc
race: "Swarm of Tiny Beasts"
class:
 - "Swarm of Ravens"
subClass:
 - "CR 1/4"
cover: "Swarm of Ravens.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1-4
  - source/xmm
---
###### Swarm of Ravens
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Swarm of Ravens.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Beasts |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Swarm of Tiny Beasts |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 12 | 5 | 12 | 6 |
| **Mod** | -2 | +2 | +1 | -3 | +1 | -2 |

**Speed:** 10 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** —
**Skills:** Perception +5
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny raven. The swarm can't regain Hit Points or gain Temporary Hit Points.


---

### Actions

**Beaks.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage, or 2 (1d4) Piercing damage if the swarm is Bloodied.

**Cacophony (Recharge 6).** wis DC 10, one creature in the swarm's space.  The target has the Deafened condition until the start of the swarm's next turn. While Deafened, the target also has Disadvantage on ability checks and attack rolls.


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