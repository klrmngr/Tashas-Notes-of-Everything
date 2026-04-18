---
type: pc
race: "Beast"
class:
 - "Frilled Deathspitter"
subClass:
 - "CR 1/2"
cover: "Frilled Deathspitter.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/1-2
  - source/psx
---
###### Frilled Deathspitter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSX
___

> [!infobox|no-t right]
> ![[Frilled Deathspitter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 18 (4d6 + 4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | PSX |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 13 | 4 | 12 | 6 |
| **Mod** | +1 | +3 | +1 | -3 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Actions

**Multiattack.** The deathspitter makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Spit Poison.** Ranged Weapon Attack: +5 to hit, range 15/30 ft., one creature. *Hit:* The target must make a DC 13 Constitution saving throw, taking 18 (4d8) poison damage on a failed save, or half as much damage on a successful one. In addition, a creature that fails its saving throw is blinded until the end of the deathspitter's next turn.


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