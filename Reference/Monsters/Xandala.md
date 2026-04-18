---
type: pc
race: "Humanoid (half-elf)"
class:
 - "Xandala"
subClass:
 - "CR 7"
cover: "Xandala.png"
campaign:
locations:
tags:
  - race/half-elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/7
  - source/toa
---
###### Xandala
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Xandala.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 71 (11d8 + 22) |
> | :FasUserGroup: Race | Humanoid (half-elf) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 11 | 14 | 18 | 16 | 18 |
| **Mod** | +0 | +0 | +2 | +4 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Draconic, Dwarvish, Elvish, Halfling
**Saving Throws:** Int +7, Wis +6
**Skills:** Arcana +7, Deception +10, History +7, Insight +6, Survival +6

---

### Traits

**Quickened Spell (3/Day).** When she casts a spell that has a casting time of 1 action, Xandala changes the casting time to 1 bonus action for that casting.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage, or 4 (1d8) bludgeoning damage when used with two hands.


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