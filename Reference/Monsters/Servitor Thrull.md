---
type: pc
race: "Construct"
class:
 - "Servitor Thrull"
subClass:
 - "CR 1/4"
cover: "Servitor Thrull.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-4
  - source/ggr
---
###### Servitor Thrull
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Servitor Thrull.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 22 (4d6 + 8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 13 | 14 | 6 | 6 | 3 |
| **Mod** | +0 | +1 | +2 | -2 | -2 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** understands Common but can't speak
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Actions

**Claws.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage.


---

### Reactions

**Self-Sacrifice.** When a creature within 5 feet of the thrull is hit by an attack, the thrull swaps places with that creature and is hit instead.


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