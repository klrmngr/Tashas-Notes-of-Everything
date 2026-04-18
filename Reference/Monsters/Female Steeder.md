---
type: pc
race: "Monstrosity"
class:
 - "Female Steeder"
subClass:
 - "CR 1"
cover: "Female Steeder.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/1
  - source/mpmm
---
###### Female Steeder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Female Steeder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 30 (4d10 + 8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 14 | 2 | 10 | 3 |
| **Mod** | +2 | +3 | +2 | -4 | +0 | -4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** —
**Skills:** Stealth +7, Perception +4

---

### Traits

**Extraordinary Leap.** The distance of the steeder's long jumps is tripled; every foot of its walking speed that it spends on the jump allows it to move 3 feet.

**Spider Climb.** The steeder can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 9 (2d8) poison damage.

**Sticky Leg.** Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller creature. *Hit:* The target is stuck to the steeder's leg and grappled (escape DC 12). The steeder can have only one creature grappled at a time.


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