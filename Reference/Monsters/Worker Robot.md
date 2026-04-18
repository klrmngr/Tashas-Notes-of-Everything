---
type: pc
race: "Construct"
class:
 - "Worker Robot"
subClass:
 - "CR 3"
cover: "Worker Robot.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/3
  - source/qftis
---
###### Worker Robot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Worker Robot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 9 | 16 | 10 | 12 | 10 |
| **Mod** | +5 | -1 | +3 | +0 | +1 | +0 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common plus the languages spoken by its creator
**Skills:** Athletics +9
**Damage Resistances:** acid; fire
**Damage Immunities:** cold; poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Lightning Overload.** When the robot takes lightning damage, it must succeed on a DC 10 Constitution saving throw or have the stunned condition until the start of its next turn.


---

### Actions

**Multiattack.** The robot makes two Cargo Tentacle attacks.

**Cargo Tentacle.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 9 (1d8 + 5) bludgeoning damage. If the target is a Medium or smaller creature, it has the grappled condition (escape DC 15). The robot has two cargo tentacles, each of which can grapple one target.

**Tractor Beam.** The robot casts Telekinesis, targeting only creatures with the incapacitated condition or objects. It requires no spell components and uses Wisdom as the spellcasting ability.


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