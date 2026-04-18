---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Thorvin Twinbeard"
subClass:
 - "CR 0"
cover: "Thorvin Twinbeard.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/0
  - source/wdh
---
###### Thorvin Twinbeard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Thorvin Twinbeard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 4 (1d8) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 10 | 10 | 10 | 16 | 10 |
| **Mod** | +0 | +0 | +0 | +0 | +3 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Dwarvish
**Damage Resistances:** poison

---

### Traits

**Dwarven Resilience.** Thorvin has advantage on saving throws against poison and resistance to poison damage.


---

### Actions

**Club.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.


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