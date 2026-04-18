---
type: pc
race: "Celestial"
class:
 - "Winged Lion"
subClass:
 - "CR 4"
cover: "Winged Lion.png"
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
###### Winged Lion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Winged Lion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 114 (12d10 + 48) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 18 | 6 | 14 | 5 |
| **Mod** | +5 | +3 | +4 | -2 | +2 | -3 |

**Speed:** 60 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** understands Celestial but can't speak

---

### Traits

**Pounce.** If the lion moves at least 20 feet straight toward a creature and then hits it with a claw attack on the same turn, that target must succeed on a DC 15 Strength saving throw or be knocked prone. If the target is prone, the lion can make one bite attack against it as a bonus action.


---

### Actions

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) slashing damage.


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