---
type: pc
race: "Beast"
class:
 - "Mammoth"
subClass:
 - "CR 6"
cover: "Mammoth.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/6
  - source/mm
---
###### Mammoth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Mammoth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 126 (11d12 + 55) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 9 | 21 | 3 | 11 | 6 |
| **Mod** | +7 | -1 | +5 | -4 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —

---

### Traits

**Trampling Charge.** If the mammoth moves at least 20 feet straight toward a creature and then hits it with a gore attack on the same turn, that target must succeed on a DC 18 Strength saving throw or be knocked prone. If the target is prone, the mammoth can make one stomp attack against it as a bonus action.


---

### Actions

**Gore.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 25 (4d8 + 7) piercing damage.

**Stomp.** Melee Weapon Attack: +10 to hit, reach 5 ft., one prone creature. *Hit:* 29 (4d10 + 7) bludgeoning damage.


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