---
type: pc
race: "Humanoid (any race)"
class:
 - "War Priest"
subClass:
 - "CR 9"
cover: "War Priest.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/9
  - source/vgm
---
###### War Priest
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[War Priest.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 117 (18d8 + 36) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 14 | 11 | 17 | 13 |
| **Mod** | +3 | +0 | +2 | +0 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any two languages
**Saving Throws:** Con +6, Wis +7
**Skills:** Intimidation +5, Religion +4

---

### Actions

**Multiattack.** The priest makes two melee attacks.

**Maul.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) bludgeoning damage.


---

### Reactions

**Guided Strike (Recharges after a Short or Long Rest).** The priest grants a +10 bonus to an attack roll made by itself or another creature within 30 feet of it. The priest can make this choice after the roll is made but before it hits or misses.


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