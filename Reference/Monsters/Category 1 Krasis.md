---
type: pc
race: "Monstrosity"
class:
 - "Category 1 Krasis"
subClass:
 - "CR 1"
cover: "Category 1 Krasis.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/ggr
---
###### Category 1 Krasis
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Category 1 Krasis.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 15 | 14 | 2 | 13 | 8 |
| **Mod** | +3 | +2 | +2 | -4 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —

---

### Traits

**Amphibious.** The krasis can breathe air and water.


---

### Actions

**Multiattack.** The krasis makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 8 (1d10 + 3) piercing damage.

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage.


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