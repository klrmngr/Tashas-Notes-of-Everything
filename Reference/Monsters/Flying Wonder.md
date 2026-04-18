---
type: pc
race: "Construct"
class:
 - "Flying Wonder"
subClass:
 - "CR 0"
cover: "Flying Wonder.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/0
  - source/fraif
---
###### Flying Wonder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Flying Wonder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 2 (1d4) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 15 | 10 | 3 | 10 | 1 |
| **Mod** | -4 | +2 | +0 | -4 | +0 | -5 |

**Speed:** 5 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 10
**Languages:** understands Common but can't speak
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Increased Carrying Capacity.** The wonder can carry up to 100 pounds.

**Wind-Up Operation.** The wonder has the Unconscious condition until another creature winds it with the wonder's unique key for 1 minute. Once wound, the wonder operates for 24 hours or until a creature touches the wonder with its key as a Utilize action to deactivate it, after which the wonder has the Unconscious condition until it is wound again.


---

### Bonus Actions

**Chime.** The wonder chirps a merry, metronomic tune. The wonder chooses one ally that it can see within 60 feet. Until the start of the wonder's next turn, the target has Advantage on the next ability check it makes with a Musical Instrument or Tinker's Tools.

**Sprint.** The wonder takes the Dash action.


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