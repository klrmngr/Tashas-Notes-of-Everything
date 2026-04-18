---
type: pc
race: "Humanoid (genasi)"
class:
 - "Miraj Vizann"
subClass:
 - "CR 6"
cover: "Miraj Vizann.png"
campaign:
locations:
tags:
  - race/genasi
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/pota
---
###### Miraj Vizann
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Miraj Vizann.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (genasi) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 10; 13 with mage armor |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Humanoid (genasi) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 10 | 17 | 13 | 11 | 18 |
| **Mod** | +1 | +0 | +3 | +1 | +0 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Primordial
**Skills:** Arcana +4, Deception +7

---

### Traits

**Earth Walk.** Moving through 3 made of earth or stone costs Miraj no extra movement.


---

### Actions

**Staff.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage when used with two hands.


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