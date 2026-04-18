---
type: pc
race: "Beast"
class:
 - "Serpopard"
subClass:
 - "CR 3"
cover: "Serpopard.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/3
  - source/psa
---
###### Serpopard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSA
___

> [!infobox|no-t right]
> ![[Serpopard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | PSA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 15 | 3 | 12 | 8 |
| **Mod** | +4 | +2 | +2 | -4 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +6

---

### Traits

**Keen Smell.** The serpopard has advantage on Wisdom (Perception) checks that rely on smell.

**Pounce.** If the serpopard moves at least 20 feet straight toward a creature and then hits it with a bite attack on the same turn, that target must succeed on a DC 14 Strength saving throw or be knocked prone. If the target is prone, the serpopard can make one bite attack against it as a bonus action.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage, and the target must make a DC 14 Constitution saving throw, taking 10 (3d6) poison damage on a failed save, or half as much damage on a successful one.


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