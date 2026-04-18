---
type: pc
race: "Plant"
class:
 - "Violet Fungus"
subClass:
 - "CR 1/4"
cover: "Violet Fungus.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-4
  - source/mm
---
###### Violet Fungus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Violet Fungus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 5 |
> | :FasHeart: HP | 18 (4d8) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 3 | 1 | 10 | 1 | 3 | 1 |
| **Mod** | -4 | -5 | +0 | -5 | -4 | -5 |

**Speed:** 5 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Condition Immunities:** blinded; deafened; frightened

---

### Traits

**False Appearance.** While the violet fungus remains motionless, it is indistinguishable from an ordinary fungus.


---

### Actions

**Multiattack.** The fungus makes 1d4 Rotting Touch attacks.

**Rotting Touch.** Melee Weapon Attack: +2 to hit, reach 10 ft., one creature. *Hit:* 4 (1d8) necrotic damage.


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