---
type: pc
race: "Beast"
class:
 - "Beast of the Land"
subClass:
 - "CR —"
cover: "Beast of the Land.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/—
  - source/tce
---
###### Beast of the Land
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Beast of the Land.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Beast |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 5 + five times your ranger level (the beast has a number of Hit Dice [d8s] equal to your ranger level) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 15 | 8 | 14 | 11 |
| **Mod** | +2 | +2 | +2 | -1 | +2 | +0 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** understands the languages you speak

---

### Traits

**Charge.** If the beast moves at least 20 feet straight toward a target and then hits it with a maul attack on the same turn, the target takes an extra 1d6 slashing damage. If the target is a creature, it must succeed on a Strength saving throw against your spell save DC or be knocked prone.

**Primal Bond.** You can add your proficiency bonus to any ability check or saving throw that the beast makes.


---

### Actions

**Maul.** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d8 + 2 + PB slashing damage.


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