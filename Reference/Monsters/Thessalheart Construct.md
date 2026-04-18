---
type: pc
race: "Construct"
class:
 - "Thessalheart Construct"
subClass:
 - "CR 0"
cover: "Thessalheart Construct.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/0
  - source/imr
---
###### Thessalheart Construct
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Thessalheart Construct.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 7 (2d4 + 2) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 12 | 10 | 10 | 7 |
| **Mod** | -3 | +2 | +1 | +0 | +0 | -2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60, passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Immunities:** poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Telepathic Bond.** While the construct is on the same plane of existence as its master, it can magically convey what it senses to its master, and the two can communicate telepathically.


---

### Actions

**Claws.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 1 slashing damage, and the target must succeed on a DC 10 Constitution saving throw or be poisoned for 1 minute. If the saving throw fails by 5 or more, the target is instead poisoned for 5 (1d10) minutes and unconscious while poisoned in this way.


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