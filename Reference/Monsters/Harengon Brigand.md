---
type: pc
race: "Humanoid"
class:
 - "Harengon Brigand"
subClass:
 - "CR 1/8"
cover: "Harengon Brigand.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/wbtw
---
###### Harengon Brigand
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Harengon Brigand.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 11 | 10 | 11 | 10 |
| **Mod** | +2 | +3 | +0 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** Common, Sylvan
**Saving Throws:** Dex +5
**Skills:** Acrobatics +5, Perception +4

---

### Traits

**Pack Tactics.** The harengon has advantage on an attack roll against a creature if at least one of the harengon's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Standing Leap.** The harengon's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.


---

### Actions

**Club.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.

**Sling.** Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage.


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