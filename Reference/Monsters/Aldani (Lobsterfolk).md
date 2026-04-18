---
type: pc
race: "Monstrosity"
class:
 - "Aldani (Lobsterfolk)"
subClass:
 - "CR 1"
cover: "Aldani (Lobsterfolk).png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/toa
---
###### Aldani (Lobsterfolk)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Aldani (Lobsterfolk).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 8 | 12 | 10 | 14 | 10 |
| **Mod** | +1 | -1 | +1 | +0 | +2 | +0 |

**Speed:** 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common
**Skills:** Perception +4, Survival +4

---

### Traits

**Amphibious.** The aldani can breathe air and water.


---

### Actions

**Multiattack.** The aldani makes two attacks with its claws.

**Claw.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage, and the target is grappled (escape DC 11). The aldani has two claws, each of which can grapple only one target.


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