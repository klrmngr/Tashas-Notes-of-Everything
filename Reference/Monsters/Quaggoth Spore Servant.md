---
type: pc
race: "Plant"
class:
 - "Quaggoth Spore Servant"
subClass:
 - "CR 1"
cover: "Quaggoth Spore Servant.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1
  - source/mm
---
###### Quaggoth Spore Servant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Quaggoth Spore Servant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 12 | 16 | 2 | 6 | 1 |
| **Mod** | +3 | +1 | +3 | -4 | -2 | -5 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), passive Perception 8
**Languages:** —
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; frightened; paralyzed; poisoned

---

### Actions

**Multiattack.** The spore servant makes two claw attacks.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.


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