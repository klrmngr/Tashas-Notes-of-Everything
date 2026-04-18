---
type: pc
race: "Construct"
class:
 - "Stone Defender"
subClass:
 - "CR 4"
cover: "Stone Defender.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/4
  - source/mtf
---
###### Stone Defender
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Stone Defender.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 3 | 10 | 1 |
| **Mod** | +4 | +0 | +3 | -4 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands one language of its creator but can't speak
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** While the stone defender remains motionless against an uneven earthen or stone surface, it is indistinguishable from that surface.

**Magic Resistance.** The stone defender has advantage on saving throws against spells and other magical effects.


---

### Actions

**Slam.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage, and if the target is Large or smaller, it is knocked prone.


---

### Reactions

**Intercept Attack.** In response to another creature within 5 feet of it being hit by an attack roll, the stone defender gives that creature a +5 bonus to its AC against that attack, potentially causing a miss. To use this ability, the stone defender must be able to see the creature and the attacker.


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