---
type: pc
race: "Elemental"
class:
 - "Merfolk Skirmisher"
subClass:
 - "CR 1/8"
cover: "Merfolk Skirmisher.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/1-8
  - source/xmm
---
###### Merfolk Skirmisher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Merfolk Skirmisher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 12 | 11 | 14 | 12 |
| **Mod** | +0 | +1 | +1 | +0 | +2 | +1 |

**Speed:** 10 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Primordial (Aquan)

---

### Traits

**Amphibious.** The merfolk can breathe air and water.


---

### Actions

**Ocean Spear.** m,r +2, reach 5 ft. or range 20/60 ft. *Hit:* 3 (1d6) Piercing damage plus 2 (1d4) Cold damage. If the target is a creature, its Speed decreases by 10 feet until the end of its next turn. The spear magically returns to the merfolk's hand immediately after a ranged attack.


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