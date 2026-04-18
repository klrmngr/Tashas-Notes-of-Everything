---
type: pc
race: "Swarm of Tiny Beasts"
class:
 - "Swarm of Venomous Snakes"
subClass:
 - "CR 2"
cover: "Swarm of Venomous Snakes.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/2
  - source/xmm
---
###### Swarm of Venomous Snakes
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Swarm of Venomous Snakes.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Beasts |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 36 (8d8) |
> | :FasUserGroup: Race | Swarm of Tiny Beasts |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 18 | 11 | 1 | 10 | 3 |
| **Mod** | -1 | +4 | +0 | -5 | +0 | -4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 10 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny snake. The swarm can't regain Hit Points or gain Temporary Hit Points.


---

### Actions

**Bites.** m +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing damage—or 6 (1d4 + 4) Piercing damage if the swarm is Bloodied—plus 10 (3d6) Poison damage.


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