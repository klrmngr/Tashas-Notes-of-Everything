---
type: pc
race: "Dragon"
class:
 - "Winged Kobold"
subClass:
 - "CR 1/4"
cover: "Winged Kobold.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/small
  - cr/1-4
  - source/xmm
---
###### Winged Kobold
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Winged Kobold.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Dragon |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 10 (4d6 - 4) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 16 | 9 | 8 | 7 | 8 |
| **Mod** | -2 | +3 | -1 | -1 | -2 | -1 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 8
**Languages:** Common, Draconic

---

### Traits

**Pack Tactics.** The kobold has Advantage on an attack roll against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.

**Sunlight Sensitivity.** While in sunlight, the kobold has Disadvantage on ability checks and attack rolls.


---

### Actions

**Dragon-Tooth Blade.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing damage.

**Chromatic Spittle.** r +5, range 30 ft. *Hit:* 6 (1d6 + 3) damage of a type chosen by the kobold: Acid, Cold, Fire, Lightning, or Poison.


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