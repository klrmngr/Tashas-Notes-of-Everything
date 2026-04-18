---
type: pc
race: "Construct"
class:
 - "Scarlet Sentinel"
subClass:
 - "CR 1"
cover: "Scarlet Sentinel.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/nrh-avitw
---
###### Scarlet Sentinel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NRH-AVitW
___

> [!infobox|no-t right]
> ![[Scarlet Sentinel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | NRH-AVitW |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 6 | 14 | 1 | 6 | 1 |
| **Mod** | +2 | -2 | +2 | -5 | -2 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** —
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Immutable Form.** The Scarlet Sentinel is immune to any spell or effect that would alter its form.

**Magic Resistance.** The Scarlet Sentinel has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The Scarlet Sentinel's weapon attacks are magical.


---

### Actions

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) bludgeoning damage.


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