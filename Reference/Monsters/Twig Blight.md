---
type: pc
race: "Plant"
class:
 - "Twig Blight"
subClass:
 - "CR 1/8"
cover: "Twig Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/1-8
  - source/mm
---
###### Twig Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Twig Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 4 (1d6 + 1) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 13 | 12 | 4 | 8 | 3 |
| **Mod** | -2 | +1 | +1 | -3 | -1 | -4 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 9
**Languages:** understands Common but can't speak
**Skills:** Stealth +3
**Damage Vulnerabilities:** fire
**Condition Immunities:** blinded; deafened

---

### Traits

**False Appearance.** While the blight remains motionless, it is indistinguishable from a dead shrub.


---

### Actions

**Claws.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.


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