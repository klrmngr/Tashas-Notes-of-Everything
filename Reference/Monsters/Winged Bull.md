---
type: pc
race: "Celestial"
class:
 - "Winged Bull"
subClass:
 - "CR 4"
cover: "Winged Bull.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/4
  - source/mot
---
###### Winged Bull
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Winged Bull.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 95 (10d10 + 40) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 18 | 6 | 10 | 5 |
| **Mod** | +5 | +2 | +4 | -2 | +0 | -3 |

**Speed:** 60 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands Celestial but can't speak

---

### Traits

**Charge.** If the bull moves at least 20 feet straight toward a creature and then hits it with a gore attack on the same turn, the target takes an extra 19 (3d12) piercing damage.


---

### Actions

**Gore.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 18 (2d12 + 5) piercing damage.


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