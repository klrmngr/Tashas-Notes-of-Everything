---
type: pc
race: "Beast"
class:
 - "Quetzalcoatlus"
subClass:
 - "CR 2"
cover: "Quetzalcoatlus.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/2
  - source/vgm
---
###### Quetzalcoatlus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Quetzalcoatlus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 30 (4d12 + 4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 13 | 13 | 2 | 10 | 5 |
| **Mod** | +2 | +1 | +1 | -4 | +0 | -3 |

**Speed:** 10 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** —
**Skills:** Perception +2

---

### Traits

**Dive Attack.** If the quetzalcoatlus is flying and dives at least 30 feet toward a target and then hits with a bite attack, the attack deals an extra 10 (3d6) damage to the target.

**Flyby.** The quetzalcoatlus doesn't provoke an opportunity attack when it flies out of an enemy's reach.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 10 ft., one creature. *Hit:* 12 (3d6 + 2) piercing damage.


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