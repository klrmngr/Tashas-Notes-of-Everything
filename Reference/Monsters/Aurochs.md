---
type: pc
race: "Beast (cattle)"
class:
 - "Aurochs"
subClass:
 - "CR 2"
cover: "Aurochs.png"
campaign:
locations:
tags:
  - race/cattle
  - affinity/hostile
  - type/beast
  - size/large
  - cr/2
  - source/mpmm
---
###### Aurochs
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Aurochs.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Beast (cattle) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 38 (4d10 + 16) |
> | :FasUserGroup: Race | Beast (cattle) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 19 | 2 | 12 | 5 |
| **Mod** | +5 | +0 | +4 | -4 | +1 | -3 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —

---

### Actions

**Gore.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage. If the aurochs moved at least 20 feet straight toward the target immediately before the hit, the target takes an extra 9 (2d8) piercing damage, and the target must succeed on a DC 15 Strength saving throw or be knocked prone if it is a creature.


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