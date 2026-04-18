---
type: pc
race: "Construct"
class:
 - "Flying Rocking Horse"
subClass:
 - "CR 1/8"
cover: "Flying Rocking Horse.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-8
  - source/wbtw
---
###### Flying Rocking Horse
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Flying Rocking Horse.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 13 | 1 | 3 | 1 |
| **Mod** | +0 | +0 | +1 | -5 | -4 | -5 |

**Speed:** 0 ft., fly 40 ft. ((only while mounted; hover)) (hover) &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** If the rocking horse is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the rocking horse move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the rocking horse is animate.

**Flying Mount.** The rocking horse can serve as a mount for a Medium or smaller creature and can fly only while mounted.

**Unusual Nature.** The rocking horse doesn't require air, food, drink, or sleep, and it regains no hit points or Hit Dice at the end of a long rest.


---

### Actions

**Head Butt.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage.


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