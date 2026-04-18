---
type: pc
race: "Beast"
class:
 - "Spiderfrog"
subClass:
 - "CR 1/4"
cover: "Spiderfrog.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/1-4
  - source/mgelft
---
###### Spiderfrog
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MGELFT
___

> [!infobox|no-t right]
> ![[Spiderfrog.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 13 (2d8 + 4) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | MGELFT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 14 | 3 | 12 | 4 |
| **Mod** | +0 | +3 | +2 | -4 | +1 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +7

---

### Traits

**Amphibious.** The spiderfrog can breathe air and water.

**Spider Climb.** The spiderfrog can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Standing Leap.** Spiderfrog's long jump is up to 20 feet and its high jump is up to 10 feet, with or without a running start.


---

### Actions

**Bite.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) piercing damage. Target is grappled (escape DC 11). Until this grapple ends, the target is restrained, and spiderfrog can't bite another target.


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