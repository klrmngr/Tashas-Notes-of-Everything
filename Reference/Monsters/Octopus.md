---
type: pc
race: "Beast"
class:
 - "Octopus"
subClass:
 - "CR 0"
cover: "Octopus.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/0
  - source/mm
---
###### Octopus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Octopus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 3 (1d6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 11 | 3 | 10 | 4 |
| **Mod** | -3 | +2 | +0 | -4 | +0 | -3 |

**Speed:** 5 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 12
**Languages:** —
**Skills:** Perception +2, Stealth +4

---

### Traits

**Hold Breath.** While out of water, the octopus can hold its breath for 30 minutes.

**Underwater Camouflage.** The octopus has advantage on Dexterity (Stealth) checks made while underwater.

**Water Breathing.** The octopus can breathe only underwater.


---

### Actions

**Tentacles.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 1 bludgeoning damage, and the target is grappled (escape DC 10). Until this grapple ends, the octopus can't use its tentacles on another target.

**Ink Cloud (Recharges after a Short or Long Rest).** A 5-foot-radius cloud of ink extends all around the octopus if it is underwater. The area is heavily obscured for 1 minute, although a significant current can disperse the ink. After releasing the ink, the octopus can use the Dash action as a bonus action.


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