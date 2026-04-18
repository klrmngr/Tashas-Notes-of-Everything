---
type: pc
race: "Fey"
class:
 - "Screaming Devilkin"
subClass:
 - "CR 1"
cover: "Screaming Devilkin.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/small
  - cr/1
  - source/mff
---
###### Screaming Devilkin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Screaming Devilkin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Fey |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 18 (4d6 + 4) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 16 | 13 | 5 | 8 | 11 |
| **Mod** | -3 | +3 | +1 | -3 | -1 | +0 |

**Speed:** 0 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 9
**Languages:** Sylvan

---

### Traits

**Agile Flier.** Opportunity attacks against the screaming devilkin have disadvantage while it is flying.

**Ceaseless Screaming.** Any creature other than a screaming devilkin that starts its turn within 30 feet of one or more screaming devilkins and can hear it must make a DC 10
Wisdom saving throw. On a failure the creature is incapacitated until the start of its next turn. On a success, the creature suffers no effect.

**Stunted Legs.** The screaming devilkin has disadvantage on attack rolls and all attack rolls made against it gain advantage while the devilkin isn't flying.


---

### Actions

**Barbed Tail.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


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