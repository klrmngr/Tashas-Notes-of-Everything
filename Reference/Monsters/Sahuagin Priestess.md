---
type: pc
race: "Humanoid (sahuagin)"
class:
 - "Sahuagin Priestess"
subClass:
 - "CR 2"
cover: "Sahuagin Priestess.png"
campaign:
locations:
tags:
  - race/sahuagin
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mm
---
###### Sahuagin Priestess
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Sahuagin Priestess.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (sahuagin) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid (sahuagin) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 11 | 12 | 12 | 14 | 13 |
| **Mod** | +1 | +0 | +1 | +1 | +2 | +1 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** Sahuagin
**Skills:** Perception +6, Religion +3

---

### Traits

**Blood Frenzy.** The sahuagin has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Limited Amphibiousness.** The sahuagin can breathe air and water, but it needs to be submerged at least once every 4 hours to avoid suffocating.

**Shark Telepathy.** The sahuagin can magically command any shark within 120 feet of it, using a limited telepathy.


---

### Actions

**Multiattack.** The sahuagin makes two melee attacks: one with her bite and one with her claws.

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.

**Claws.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) slashing damage.


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