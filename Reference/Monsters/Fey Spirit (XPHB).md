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
  - source/xphb
---
###### Fey Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Fey Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 30 + 10 for each spell level above 3 |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 14 | 14 | 11 | 16 |
| **Mod** | +1 | +3 | +2 | +2 | +0 | +3 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Sylvan, understands the languages you know
**Condition Immunities:** charmed

---

### Actions

**Multiattack.** The spirit makes a number of Fey Blade attacks equal to half this spell's level (round down).

**Fey Blade.** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 2d6 + 3 + summonSpellLevel Force damage.


---

### Bonus Actions

**Fey Step.** The spirit magically teleports up to 30 feet to an unoccupied space it can see. Then one of the following effects occurs, based on the spirit's chosen mood:
- **Fuming.** The spirit has Advantage on the next attack roll it makes before the end of this turn.
- **Mirthful.** wis DC equals your spell save DC, one creature the spirit can see within 10 feet of itself.  The target is Charmed by you and the spirit for 1 minute or until the target takes any damage.
- **Tricksy.** The spirit fills a 10-foot Cube within 5 feet of it with magical Darkness, which lasts until the end of its next turn.


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