---
type: pc
race: "Plant"
class:
 - "Awakened Tree"
subClass:
 - "CR 2"
cover: "Awakened Tree.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/2
  - source/mm
---
###### Awakened Tree
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Awakened Tree.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 59 (7d12 + 14) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 6 | 15 | 10 | 10 | 7 |
| **Mod** | +4 | -2 | +2 | +0 | +0 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** one language known by its creator
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing

---

### Traits

**False Appearance.** While the tree remains motionless, it is indistinguishable from a normal tree.


---

### Actions

**Slam.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 14 (3d6 + 4) bludgeoning damage.


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