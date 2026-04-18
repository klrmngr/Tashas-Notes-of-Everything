---
type: pc
race: "Swarm of Tiny Beasts"
class:
 - "Swarm of Piranhas"
subClass:
 - "CR 1"
cover: "Swarm of Piranhas.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1
  - source/xmm
---
###### Swarm of Piranhas
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Swarm of Piranhas.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Swarm of Tiny Beasts |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 28 (8d8 - 8) |
> | :FasUserGroup: Race | Swarm of Tiny Beasts |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 9 | 1 | 7 | 2 |
| **Mod** | +1 | +3 | -1 | -5 | -2 | -4 |

**Speed:** 5 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 8
**Languages:** —
**Damage Resistances:** bludgeoning; piercing; slashing
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; prone; restrained; stunned

---

### Traits

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Tiny piranha. The swarm can't regain Hit Points or gain Temporary Hit Points.

**Water Breathing.** The swarm can breathe only underwater.


---

### Actions

**Bites.** m +5 (with Advantage if the target doesn't have all its Hit Points), reach 5 ft. *Hit:* 8 (2d4 + 3) Piercing damage, or 5 (1d4 + 3) Piercing damage if the swarm is Bloodied.


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