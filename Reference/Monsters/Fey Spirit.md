---
type: pc
race: "Fey"
class:
 - "Fey Spirit"
subClass:
 - "CR —"
cover: "Fey Spirit.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/—
  - source/tce
---
###### Fey Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Fey Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 30 + 10 for each spell level above 3rd |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 14 | 14 | 11 | 16 |
| **Mod** | +1 | +3 | +2 | +2 | +0 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Sylvan, understands the languages you speak
**Condition Immunities:** charmed

---

### Actions

**Multiattack.** The fey makes a number of attacks equal to half this spell's level (rounded down).

**Shortsword.** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d6 + 3 + summonSpellLevel piercing damage + 1d6 force damage.


---

### Bonus Actions

**Fey Step.** The fey magically teleports up to 30 feet to an unoccupied space it can see. Then one of the following effects occurs, based on the fey's chosen mood:
- **Fuming.** The fey has advantage on the next attack roll it makes before the end of this turn.
- **Mirthful.** The fey can force one creature it can see within 10 feet of it to make a Wisdom saving throw against your spell save DC. Unless the save succeeds, the target is charmed by you and the fey for 1 minute or until the target takes any damage.
- **Tricksy.** The fey can fill a 5-foot cube within 5 feet of it with magical darkness, which lasts until the end of its next turn.


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