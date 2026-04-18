---
type: pc
race: "Monstrosity"
class:
 - "Gremishka"
subClass:
 - "CR 1/8"
cover: "Gremishka.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/1-8
  - source/vrgr
---
###### Gremishka
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Gremishka.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 10 (4d4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 10 | 12 | 11 | 4 |
| **Mod** | -2 | +2 | +0 | +1 | +0 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 10
**Languages:** understands Common but can't speak

---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 2 (1d4 + 2) piercing damage plus 3 (1d6) force damage.


---

### Reactions

**Magic Allergy (1/Day).** Immediately after a creature within 30 feet of the gremishka casts a spell, the gremishka can spontaneously react to the magic. Roll a d6 to determine the effect:
- **1-2.** The gremishka emanates magical energy. Each creature within 30 feet of the gremishka must succeed on a DC 10 Constitution saving throw or take 3 (1d6) force damage.
- **3-4.** The gremishka surges with magical energy and regains 3 (1d6) hit points.
- **5-6.** The gremishka explodes and dies, and one swarm of gremishkas instantly appears in the space where this gremishka died. The swarm uses the gremishka's initiative.


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