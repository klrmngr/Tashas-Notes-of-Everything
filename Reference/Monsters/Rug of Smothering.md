---
type: pc
race: "Construct"
class:
 - "Rug of Smothering"
subClass:
 - "CR 2"
cover: "Rug of Smothering.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/2
  - source/mm
---
###### Rug of Smothering
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Rug of Smothering.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 33 (6d10) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 10 | 1 | 3 | 1 |
| **Mod** | +3 | +2 | +0 | -5 | -4 | -5 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; frightened; paralyzed; petrified; poisoned

---

### Traits

**Antimagic Susceptibility.** The rug is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the rug must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.

**Damage Transfer.** While it is grappling a creature, the rug takes only half the damage dealt to it, and the creature grappled by the rug takes the other half.

**False Appearance.** While the rug remains motionless, it is indistinguishable from a normal rug.


---

### Actions

**Smother.** Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller creature. *Hit:* The creature is grappled (escape DC 13). Until this grapple ends, the target is restrained, blinded, and at risk of suffocating, and the rug can't smother another target. In addition, at the start of each of the target's turns, the target takes 10 (2d6 + 3) bludgeoning damage.


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