---
type: pc
race: "Swarm of Small Fiends (demon)"
class:
 - "Swarm of Dretches"
subClass:
 - "CR 4"
cover: "Swarm of Dretches.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/4
  - source/xmm
---
###### Swarm of Dretches
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Swarm of Dretches.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Swarm of Small Fiends (demon) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Swarm of Small Fiends (demon) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 14 | 5 | 8 | 3 |
| **Mod** | +2 | +0 | +2 | -3 | -1 | -4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 9
**Languages:** Abyssal; telepathy 60 ft. (works only with creatures that understand Abyssal)
**Damage Resistances:** bludgeoning; cold; fire; lightning; piercing; slashing
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Fetid Aura.** con DC 12, any creature that starts its turn in a 10-foot Emanation originating from the swarm.  The target has the Poisoned condition until the start of its next turn. While Poisoned, the target can take either an action or a Bonus Action on its turn, not both, and it can't take Reactions.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through any opening large enough for a Small creature. The swarm can't regain Hit Points or gain Temporary Hit Points.


---

### Actions

**Multiattack.** The swarm makes two Rend attacks.

**Rend.** m +4, reach 5 ft. *Hit:* 12 (3d6 + 2) Slashing damage, or 9 (3d4 + 2) Slashing damage if the swarm is Bloodied.


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