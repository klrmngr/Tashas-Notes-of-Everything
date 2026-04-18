---
type: pc
race: "Construct"
class:
 - "Winged Thrull"
subClass:
 - "CR 1/2"
cover: "Winged Thrull.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-2
  - source/ggr
---
###### Winged Thrull
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Winged Thrull.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 31 (7d6 + 7) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 15 | 12 | 8 | 9 | 8 |
| **Mod** | -1 | +2 | +1 | -1 | -1 | -1 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** understands Common but can't speak
**Saving Throws:** Dex +4
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Actions

**Claws.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) slashing damage.

**Rock.** Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.


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