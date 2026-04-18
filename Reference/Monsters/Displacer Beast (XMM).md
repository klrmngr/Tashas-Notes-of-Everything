---
type: pc
race: "Monstrosity"
class:
 - "Displacer Beast"
subClass:
 - "CR 3"
cover: "Displacer Beast.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/xmm
---
###### Displacer Beast
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Displacer Beast.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 76 (9d10 + 27) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 6 | 12 | 8 |
| **Mod** | +4 | +2 | +3 | -2 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** understands Sylvan but can't speak

---

### Traits

**Avoidance.** If the displacer beast is subjected to an effect that allows it to make a saving throw to take only half damage, it instead takes no damage if it succeeds on the save and half damage if it fails. It can't use this trait if it has the Incapacitated condition.

**Displacement.** Attack rolls against the displacer beast have Disadvantage, since it projects an illusion that makes it appear to be near its actual location. This trait is suppressed while the displacer beast has the Incapacitated condition.


---

### Actions

**Multiattack.** The displacer beast makes one Rend attack and one Tentacle attack.

**Rend.** m +6, reach 5 feet. *Hit:* 9 (1d10 + 4) Slashing damage. If target is a Large or smaller creature, it has the Prone condition.

**Tentacle.** m +6, reach 10 feet. *Hit:* 11 (2d6 + 4) Piercing damage.


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