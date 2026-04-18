---
type: pc
race: "Undead"
class:
 - "Giant Shark Skeleton"
subClass:
 - "CR 5"
cover: "Giant Shark Skeleton.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/5
  - source/sdw
---
###### Giant Shark Skeleton
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: SDW
___

> [!infobox|no-t right]
> ![[Giant Shark Skeleton.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 126 (11d12 + 55) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | SDW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 11 | 21 | 1 | 10 | 5 |
| **Mod** | +6 | +0 | +5 | -5 | +0 | -3 |

**Speed:** 20 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Blood Frenzy.** The giant shark skeleton has advantage on melee attack rolls against any creature that doesn't have all its hit points.


---

### Actions

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 22 (3d10 + 6) piercing damage.


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