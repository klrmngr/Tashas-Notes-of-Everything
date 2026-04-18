---
type: pc
race: "Plant"
class:
 - "Spore Servant Octopus"
subClass:
 - "CR 1"
cover: "Spore Servant Octopus.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/1
  - source/dosi
---
###### Spore Servant Octopus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DoSI
___

> [!infobox|no-t right]
> ![[Spore Servant Octopus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 52 (8d10 + 8) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | DoSI |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 13 | 13 | 2 | 6 | 1 |
| **Mod** | +3 | +1 | +1 | -4 | -2 | -5 |

**Speed:** 5 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 8
**Languages:** —
**Condition Immunities:** blinded; charmed; frightened; paralyzed

---

### Traits

**Hold Breath.** While out of water, the octopus can hold its breath for 1 hour.

**Water Breathing.** The octopus can breathe only underwater.


---

### Actions

**Tentacles.** Melee Weapon Attack: +5 to hit, reach 15 ft., one target *Hit:* 7 (1d8 + 3) bludgeoning damage.


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