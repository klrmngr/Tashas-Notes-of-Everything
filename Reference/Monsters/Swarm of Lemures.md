---
type: pc
race: "Swarm of Medium Fiends (devil)"
class:
 - "Swarm of Lemures"
subClass:
 - "CR 3"
cover: "Swarm of Lemures.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/3
  - source/xmm
---
###### Swarm of Lemures
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Swarm of Lemures.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Swarm of Medium Fiends (devil) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Swarm of Medium Fiends (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 7 | 14 | 1 | 12 | 3 |
| **Mod** | +2 | -2 | +2 | -5 | +1 | -4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 11
**Languages:** understands Infernal but can't speak
**Damage Resistances:** bludgeoning; cold; piercing; slashing
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; stunned

---

### Traits

**Hellish Restoration.** If the swarm dies in the Nine Hells, it revives with all its Hit Points in 1d10 days unless it is killed by a creature under the effects of a Bless spell or its remains are sprinkled with Holy Water.

**Swarm.** The swarm can occupy another creature's space and vice versa, and the swarm can move through an opening large enough for a Medium creature. The swarm can't regain Hit Points or gain Temporary Hit Points.


---

### Actions

**Multiattack.** The swarm makes two Vile Slime attacks.

**Vile Slime.** m +4, reach 5 ft. *Hit:* 11 (2d8 + 2) Poison damage, or 9 (2d6 + 2) Poison damage if the swarm is Bloodied.


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