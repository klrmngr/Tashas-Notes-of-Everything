---
type: pc
race: "Plant"
class:
 - "Twig Blight"
subClass:
 - "CR 1/8"
cover: "Twig Blight.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/1-8
  - source/xmm
---
###### Twig Blight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Twig Blight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 11 | 4 | 8 | 3 |
| **Mod** | -2 | +2 | +0 | -3 | -1 | -4 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 9
**Languages:** understands Common but can't speak
**Skills:** Stealth +4
**Damage Vulnerabilities:** fire
**Condition Immunities:** deafened

---

### Traits

**Pack Tactics.** The blight has Advantage on an attack roll against a creature if at least one of the blight's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Claw.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Slashing damage.


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