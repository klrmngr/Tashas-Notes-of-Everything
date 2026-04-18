---
type: pc
race: "Beast"
class:
 - "Dolphin"
subClass:
 - "CR 1/8"
cover: "Dolphin.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/medium
  - cr/1-8
  - source/mpmm
---
###### Dolphin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Dolphin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Beast |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 13 | 13 | 6 | 12 | 7 |
| **Mod** | +2 | +1 | +1 | -2 | +1 | -2 |

**Speed:** 0 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3

---

### Traits

**Hold Breath.** The dolphin can hold its breath for 20 minutes.


---

### Actions

**Slam.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage. If the dolphin moved at least 30 feet straight toward the target immediately before the hit, the target takes an extra 3 (1d6) bludgeoning damage.


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