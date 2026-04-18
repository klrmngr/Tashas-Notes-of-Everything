---
type: pc
race: "Elemental"
class:
 - "Polar Serpent"
subClass:
 - "CR 3"
cover: "Polar Serpent.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/large
  - cr/3
  - source/fraif
---
###### Polar Serpent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Polar Serpent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Elemental |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 58 (9d10 + 9) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 19 | 12 | 4 | 12 | 6 |
| **Mod** | +4 | +4 | +1 | -3 | +1 | -2 |

**Speed:** 40 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** understands Primordial but can't speak
**Skills:** Perception +3, Stealth +6
**Damage Vulnerabilities:** fire
**Damage Immunities:** cold

---

### Traits

**Misty Slithering.** The serpent can move through a space as narrow as 1 inch without expending extra movement to do so.


---

### Actions

**Multiattack.** The serpent makes one Bite attack and uses Constrict.

**Bite.** m +6, reach 5 ft. *Hit:* 8 (1d8 + 4) Piercing damage plus 3 (1d6) Cold damage.

**Constrict.** str DC 14, one Medium or smaller creature the snake can see within 10 feet.  3 (1d6) Bludgeoning damage plus 7 (2d6) Cold damage. The target has the Grappled condition (escape DC 14), and it has the Restrained condition until the grapple ends.


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