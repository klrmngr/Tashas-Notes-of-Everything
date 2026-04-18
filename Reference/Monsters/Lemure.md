---
type: pc
race: "Fiend (devil)"
class:
 - "Lemure"
subClass:
 - "CR 0"
cover: "Lemure.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/0
  - source/mm
---
###### Lemure
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Lemure.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 7 |
> | :FasHeart: HP | 13 (3d8) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 5 | 11 | 1 | 11 | 3 |
| **Mod** | +0 | -3 | +0 | -5 | +0 | -4 |

**Speed:** 15 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands Infernal but can't speak
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Devil's Sight.** Magical darkness doesn't impede the lemure's darkvision.

**Hellish Rejuvenation.** A lemure that dies in the Nine Hells comes back to life with all its hit points in 1d10 days unless it is killed by a good-aligned creature with a bless spell cast on that creature or its remains are sprinkled with holy water.


---

### Actions

**Fist.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.


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