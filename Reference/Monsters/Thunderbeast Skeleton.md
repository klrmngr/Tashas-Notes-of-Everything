---
type: pc
race: "Undead"
class:
 - "Thunderbeast Skeleton"
subClass:
 - "CR 3"
cover: "Thunderbeast Skeleton.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/3
  - source/skt
---
###### Thunderbeast Skeleton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Thunderbeast Skeleton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 68 (8d12 + 16) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 15 | 2 | 12 | 5 |
| **Mod** | +4 | +0 | +2 | -4 | +1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** —
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** poisoned; exhaustion

---

### Actions

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., *Hit:* 18 (4d6 + 4) piercing damage.

**Tail.** +7 to hit, reach 10 ft., one target. *Hit:* 18 (4d6 + 4) bludgeoning damage. Succeed on a DC14 Strength saving throw or be knocked prone.


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