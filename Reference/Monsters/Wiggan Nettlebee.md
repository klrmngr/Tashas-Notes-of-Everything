---
type: pc
race: "Humanoid (halfling)"
class:
 - "Wiggan Nettlebee"
subClass:
 - "CR 2"
cover: "Wiggan Nettlebee.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/pota
---
###### Wiggan Nettlebee
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Wiggan Nettlebee.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11; 16 with barkskin |
> | :FasHeart: HP | 36 (8d6 + 8) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 12 | 12 | 14 | 15 | 13 |
| **Mod** | -1 | +1 | +1 | +2 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Halfling
**Skills:** Deception +3, Insight +4

---

### Traits

**Brave Devotion.** Wiggan has advantage on saving throws against being charmed or frightened.


---

### Actions

**Multiattack.** Wiggan makes two attacks with his wooden cane.

**Wooden Cane.** Melee Weapon Attack: +0 to hit (+4 to hit with shillelagh), reach 5 ft., one target. *Hit:* 1 (1d4 - 1) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage with shillelagh.


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