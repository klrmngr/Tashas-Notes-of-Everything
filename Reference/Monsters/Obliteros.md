---
type: pc
race: "Beast"
class:
 - "Obliteros"
subClass:
 - "CR 5"
cover: "Obliteros.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/5
  - source/wdh
---
###### Obliteros
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Obliteros.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 126 (11d12 + 55) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 11 | 21 | 10 | 10 | 5 |
| **Mod** | +6 | +0 | +5 | +0 | +0 | -3 |

**Speed:** 0 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 13
**Languages:** Aquan
**Skills:** Perception +3

---

### Traits

**Blood Frenzy.** Obliteros has advantage on melee attack rolls against any creature that doesn't have all its hit points.

**Water Breathing.** Obliteros can breathe only underwater.


---

### Actions

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 22 (3d10 + 6) piercing damage.


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