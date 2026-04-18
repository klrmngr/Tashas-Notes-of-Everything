---
type: pc
race: "Humanoid"
class:
 - "Witchlight Hand (Medium)"
subClass:
 - "CR 1/8"
cover: "Witchlight Hand (Medium).png"
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
###### Witchlight Hand (Medium)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Witchlight Hand (Medium).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 11 | 12 | 13 | 12 |
| **Mod** | +0 | +2 | +0 | +1 | +1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common plus any one language
**Skills:** Sleight Of Hand +6

---

### Traits

**Secret Expertise.** The hand has one of these additional skills: Acrobatics DC 6 Acrobatics check, Animal Handling DC 5 Animal_handling check, Arcana DC 5 Arcana check, Athletics DC 4 Athletics check, Medicine DC 5 Medicine check, or Performance DC 5 Performance check.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Pixie Dust (1/Day).** The hand sprinkles a pinch of pixie dust on itself or another creature it can see within 5 feet of it. The recipient gains a flying speed of 30 feet for 1 minute. If the creature is airborne when this effect ends, it falls safely to the ground, taking no damage and landing on its feet.


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