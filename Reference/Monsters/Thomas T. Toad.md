---
type: pc
race: "Construct"
class:
 - "Thomas T. Toad"
subClass:
 - "CR 2"
cover: "Thomas T. Toad.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/2
  - source/rmbre
---
###### Thomas T. Toad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: RMBRE
___

> [!infobox|no-t right]
> ![[Thomas T. Toad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 11 (hide armor) |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | RMBRE |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 8 | 16 | 5 | 7 | 7 |
| **Mod** | +4 | -1 | +3 | -3 | -2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** Common
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Actions

**Webby Hands.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage.


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