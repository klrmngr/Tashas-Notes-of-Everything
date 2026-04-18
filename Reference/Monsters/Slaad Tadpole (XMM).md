---
type: pc
race: "Aberration"
class:
 - "Slaad Tadpole"
subClass:
 - "CR 1/8"
cover: "Slaad Tadpole.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/tiny
  - cr/1-8
  - source/xmm
---
###### Slaad Tadpole
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Slaad Tadpole.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Aberration |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 7 (3d4) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 15 | 10 | 3 | 5 | 3 |
| **Mod** | -2 | +2 | +0 | -4 | -3 | -4 |

**Speed:** 30 ft., burrow 10 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 7
**Languages:** understands Slaad but can't speak
**Skills:** Stealth +4
**Damage Resistances:** acid; cold; fire; lightning; thunder

---

### Traits

**Magic Resistance.** The slaad has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Bite.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage.


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