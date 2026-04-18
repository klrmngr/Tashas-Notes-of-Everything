---
type: pc
race: "Monstrosity"
class:
 - "Xill"
subClass:
 - "CR 3"
cover: "Xill.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/mff
---
###### Xill
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Xill.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 13 | 11 | 14 | 9 |
| **Mod** | +2 | +4 | +1 | +0 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common
**Skills:** Acrobatics +6, Athletics +4, Perception +4

---

### Traits

**Ethereal Jaunt.** As a bonus action, a xill can magically shift from the Material Plane to the Ethereal Plane, or vice versa.

**Poison Stinger.** The xill injects poison into one creature it hit with its claws this turn. The chosen creature must make a DC 11 Constitution saving throw, with disadvantage if the xill hit it more than once this turn, taking 14 (4d6) poison damage on a failed save, or half as much on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but poisoned for 1 hour, even after regaining hit points, and is paralyzed while poisoned this way.


---

### Actions

**Multiattack.** The xill makes four claw attacks.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.


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