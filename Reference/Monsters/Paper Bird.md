---
type: pc
race: "Construct"
class:
 - "Paper Bird"
subClass:
 - "CR 0"
cover: "Paper Bird.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/0
  - source/wbtw
---
###### Paper Bird
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Paper Bird.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 1 (1d4 - 1) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 5 | 16 | 8 | 2 | 14 | 6 |
| **Mod** | -3 | +3 | -1 | -4 | +2 | -2 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Skills:** Perception +4
**Damage Vulnerabilities:** fire
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; exhaustion; frightened; poisoned

---

### Traits

**Keen Sight.** The paper bird has advantage on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Sharp Edges.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 1 slashing damage.


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