---
type: pc
race: "Monstrosity"
class:
 - "Male Steeder"
subClass:
 - "CR 1/4"
cover: "Male Steeder.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1-4
  - source/mtf
---
###### Male Steeder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Male Steeder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 14 | 2 | 10 | 3 |
| **Mod** | +2 | +1 | +2 | -4 | +0 | -4 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** —
**Skills:** Stealth +5, Perception +4

---

### Traits

**Spider Climb.** The steeder can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Extraordinary Leap.** The distance of the steeder's long jumps is tripled; every foot of its walking speed that it spends on the jump allows it to jump 3 feet.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage plus 4 (1d8) poison damage.

**Sticky Leg.** Melee Weapon Attack: +4 to hit, reach 5 ft., one Small or Tiny creature. *Hit:* The target is stuck to the steeder's leg and is grappled until it escapes (escape DC 12). The steeder can have only one creature grappled at a time.


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