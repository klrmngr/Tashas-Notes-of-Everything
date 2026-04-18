---
type: pc
race: "Construct"
class:
 - "Tin Soldier"
subClass:
 - "CR 1"
cover: "Tin Soldier.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1
  - source/wbtw
---
###### Tin Soldier
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Tin Soldier.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 27 (6d6 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 13 | 1 | 3 | 1 |
| **Mod** | +2 | +0 | +1 | -5 | -4 | -5 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Antimagic Susceptibility.** The tin soldier is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the tin soldier must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.

**False Appearance.** While the tin soldier remains motionless, it is indistinguishable from a normal suit of armor.


---

### Actions

**Multiattack.** The tin soldier makes two melee attacks.

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.


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