---
type: pc
race: "Beast"
class:
 - "Female Steeder"
subClass:
 - "CR 1"
cover: "Female Steeder.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1
  - source/oota
---
###### Female Steeder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Female Steeder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 30 (4d10 + 8) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 14 | 2 | 10 | 3 |
| **Mod** | +2 | +3 | +2 | -4 | +0 | -4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** —
**Skills:** Stealth +7

---

### Traits

**Spider Climb.** The steeder can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Leap.** The steeder can expend all its movement on its turn to jump up to 90 feet vertically or horizontally, provided that its speed is at least 30 feet.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 7 (1d8 + 3) piercing damage, and the target must make a DC 12 Constitution saving throw, taking 9 (2d8) acid damage on a failed save, or half as much damage on a successful one.

**Sticky Leg (Recharges when the Steeder Has No Creatures Grappled).** Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller creature. *Hit:* The target is stuck to the steeder's leg and grappled until it escapes (escape DC 12).


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