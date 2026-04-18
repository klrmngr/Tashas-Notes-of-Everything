---
type: pc
race: "Aberration (gith)"
class:
 - "Githzerai Traveler"
subClass:
 - "CR 3"
cover: "Githzerai Traveler.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/3
  - source/mpp
---
###### Githzerai Traveler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Githzerai Traveler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Aberration (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (psychic defense) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Aberration (gith) |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 12 | 14 | 16 | 10 |
| **Mod** | +1 | +2 | +1 | +2 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Gith
**Saving Throws:** Str +3, Dex +4, Int +4, Wis +5
**Skills:** Perception +5, Survival +5

---

### Traits

**Psychic Defense.** While the githzerai is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The githzerai makes three Unarmed Strike attacks.

**Unarmed Strike.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage plus 4 (1d8) psychic damage.


---

### Bonus Actions

**Matter Manipulation (Recharge 4–6).** The githzerai manipulates the energy of the plane of existence it's on to produce one of the following effects (choose one or roll a d6):
- **1-2: Astral Step.** The githzerai can teleport, along with any equipment it is wearing or carrying, up to 40 feet to an unoccupied space it can see. In addition, its walking speed increases to 40 feet until the start of its next turn.
- **3-4: Growth.** Flowers and vines grow around the githzerai until the start of its next turn, then vanish; the ground within 15 feet of the githzerai is difficult terrain for other creatures while the flowers and vines are present.
- **5-6: Retaliating Light.** Multicolored lights surround the githzerai until the start of its next turn. For the effect's duration, whenever a creature within 5 feet of the githzerai hits it with a melee attack roll, that creature takes 3 (1d6) force damage, as magic lashes out in retribution.


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