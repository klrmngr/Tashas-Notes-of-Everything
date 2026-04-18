---
type: pc
race: "Monstrosity"
class:
 - "Manticore"
subClass:
 - "CR 3"
cover: "Manticore.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/mm
---
###### Manticore
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Manticore.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 17 | 7 | 12 | 8 |
| **Mod** | +3 | +3 | +3 | -2 | +1 | -1 |

**Speed:** 30 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common

---

### Traits

**Tail Spike Regrowth.** The manticore has twenty-four tail spikes. Used spikes regrow when the manticore finishes a long rest.


---

### Actions

**Multiattack.** The manticore makes three attacks: one with its bite and two with its claws or three with its tail spikes.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Tail Spike.** Ranged Weapon Attack: +5 to hit, range 100/200 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage.


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