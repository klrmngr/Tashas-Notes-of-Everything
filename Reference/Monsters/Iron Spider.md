---
type: pc
race: "Construct"
class:
 - "Iron Spider"
subClass:
 - "CR —"
cover: "Iron Spider.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/—
  - source/wdmm
---
###### Iron Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Iron Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 80 |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 10 | 3 | 3 | 1 |
| **Mod** | +4 | +0 | +0 | -4 | -4 | -5 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Damage Immunities:** poison; psychic

---

### Traits

**Spider Climb.** The iron spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Antimagic Susceptibility.** The iron spider is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the iron spider must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.


---

### Actions

**Web Cable.** The iron spider shoots out a 6-inch-thick web cable up to 50 feet long, attaching the far end of the cable to a solid surface up to 50 feet away from it. As a bonus action, it can detach the other end of the cable from itself and attach it to a solid surface within 10 feet of it. Once it creates 200 feet of web cable, the spider can't produce any more cable until the next dawn.


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