---
type: pc
race: "Humanoid (any race)"
class:
 - "Pirate First Mate"
subClass:
 - "CR 1"
cover: "Pirate First Mate.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/gos
---
###### Pirate First Mate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Pirate First Mate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 14 | 11 | 10 | 13 |
| **Mod** | +2 | +0 | +2 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** any one language (usually Common)
**Skills:** Athletics +4, Intimidation +3

---

### Traits

**Sea Legs.** The first mate has advantage on ability checks and saving throws to resist being knocked prone.


---

### Actions

**Multiattack.** The first mate makes two attacks with its longsword.

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands. If the target is a creature, the first mate can choose to deal no damage with the attack to disarm the target. The target must succeed on a DC 14 Strength saving throw or drop one item it is holding on the ground.


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