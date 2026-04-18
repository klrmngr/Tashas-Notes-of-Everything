---
type: pc
race: "Monstrosity"
class:
 - "Homarid"
subClass:
 - "CR 1"
cover: "Homarid.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/psd
---
###### Homarid
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSD
___

> [!infobox|no-t right]
> ![[Homarid.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | PSD |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 8 | 13 | 9 | 14 | 10 |
| **Mod** | +1 | -1 | +1 | -1 | +2 | +0 |

**Speed:** 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Homarid
**Skills:** Perception +4, Stealth +3

---

### Traits

**Amphibious.** The homarid can breathe air and water.


---

### Actions

**Multiattack.** The homarid makes two claw attacks.

**Claw.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage, and the target is grappled (escape DC 11). The homarid has two claws, each of which can grapple only one target.


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