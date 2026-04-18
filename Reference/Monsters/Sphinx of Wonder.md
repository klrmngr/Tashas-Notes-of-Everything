---
type: pc
race: "Celestial"
class:
 - "Sphinx of Wonder"
subClass:
 - "CR 1"
cover: "Sphinx of Wonder.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/tiny
  - cr/1
  - source/xmm
---
###### Sphinx of Wonder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Sphinx of Wonder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Celestial |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 24 (7d4 + 7) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 17 | 13 | 15 | 12 | 11 |
| **Mod** | -2 | +3 | +1 | +2 | +1 | +0 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 11
**Languages:** Celestial, Common
**Skills:** Arcana +4, Religion +4, Stealth +5
**Damage Resistances:** necrotic; psychic; radiant

---

### Traits

**Magic Resistance.** The sphinx has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Rend.** m +5, reach 5 ft. *Hit:* 5 (1d4 + 3) Slashing damage plus 7 (2d6) Radiant damage.


---

### Reactions

**Burst of Ingenuity (2/Day).**  The sphinx or another creature within 30 feet makes an ability check or a saving throw.  The sphinx adds 2 to the roll.


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