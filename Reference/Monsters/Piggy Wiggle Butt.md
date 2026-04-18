---
type: pc
race: "Construct"
class:
 - "Piggy Wiggle Butt"
subClass:
 - "CR 1/2"
cover: "Piggy Wiggle Butt.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-2
  - source/rmbre
---
###### Piggy Wiggle Butt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: RMBRE
___

> [!infobox|no-t right]
> ![[Piggy Wiggle Butt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (hide armor) |
> | :FasHeart: HP | 15 (2d8 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | RMBRE |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 16 | 7 | 11 | 10 |
| **Mod** | +3 | +1 | +3 | -2 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common
**Skills:** Intimidation +2
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Aggressive.** As a bonus action, Piggy Wiggle Butt can move up to its speed toward a hostile creature that it can see.


---

### Actions

**Clay Jug.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage.


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