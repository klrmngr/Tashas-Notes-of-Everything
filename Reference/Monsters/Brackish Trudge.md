---
type: pc
race: "Plant"
class:
 - "Brackish Trudge"
subClass:
 - "CR 3"
cover: "Brackish Trudge.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/3
  - source/scc
---
###### Brackish Trudge
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Brackish Trudge.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 17 | 4 | 14 | 4 |
| **Mod** | +5 | +0 | +3 | -3 | +2 | -3 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4
**Damage Resistances:** fire

---

### Traits

**Fungal Fortitude.** If damage reduces the trudge to 0 hit points, it must make a Constitution saving throw with a DC of 5 + the damage taken, unless the damage is radiant or from a critical hit. On a success, the trudge drops to 1 hit point instead.


---

### Actions

**Tusk.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage plus 3 (1d6) poison damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.


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