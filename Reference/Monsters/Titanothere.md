---
type: pc
race: "Beast"
class:
 - "Titanothere"
subClass:
 - "CR 5"
cover: "Titanothere.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/5
  - source/bgg
---
###### Titanothere
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Titanothere.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 136 (13d12 + 52) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 10 | 19 | 2 | 12 | 6 |
| **Mod** | +7 | +0 | +4 | -4 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —

---

### Traits

**Beast of Burden.** The titanothere is considered to be one size larger for the purpose of determining its carrying capacity.


---

### Actions

**Stomp.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 20 (3d8 + 7) bludgeoning damage. If the titanothere moved at least 20 feet straight toward the target immediately before the hit, the target takes an extra 13 (3d8) bludgeoning damage, and the target must succeed on a DC 18 Strength saving throw or have the prone condition if it is a creature.


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