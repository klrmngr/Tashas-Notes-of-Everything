---
type: pc
race: "Construct"
class:
 - "Billy Beaver"
subClass:
 - "CR 3"
cover: "Billy Beaver.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/3
  - source/rmbre
---
###### Billy Beaver
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: RMBRE
___

> [!infobox|no-t right]
> ![[Billy Beaver.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 34 (7d10 + 21) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | RMBRE |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 17 | 3 | 12 | 7 |
| **Mod** | +5 | +1 | +3 | -4 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common
**Skills:** Perception +3
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Keen Sight and Smell.** Billy Beaver has advantage on Wisdom (Perception) checks that rely on sight or smell.


---

### Actions

**Beak.** Melee Weapon Attack: +7 to hit, reach 5 ft., one creature. *Hit:* 10 (1d10 + 5) piercing damage.


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