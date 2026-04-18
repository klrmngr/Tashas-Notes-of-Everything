---
type: pc
race: "Construct"
class:
 - "Constructed Commoner"
subClass:
 - "CR 0"
cover: "Constructed Commoner.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/0
  - source/cm
---
###### Constructed Commoner
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Constructed Commoner.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 6 (1d8 + 2) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 15 | 10 | 10 | 10 |
| **Mod** | +0 | +0 | +2 | +0 | +0 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Unusual Nature.** The commoner doesn't require air, food, drink, or sleep, and it gains no benefit from finishing a short or long rest. When it drops to 0 hit points, it becomes a lifeless object.


---

### Actions

**Club.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.


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