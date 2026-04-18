---
type: pc
race: "Humanoid"
class:
 - "Setessan Hoplite"
subClass:
 - "CR 4"
cover: "Setessan Hoplite.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/mot
---
###### Setessan Hoplite
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Setessan Hoplite.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (leather, shield) |
> | :FasHeart: HP | 58 (9d8 + 18) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 14 | 13 | 16 | 11 |
| **Mod** | +2 | +3 | +2 | +1 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common
**Saving Throws:** Dex +5, Wis +5
**Skills:** Acrobatics +5, Perception +5, Survival +5

---

### Traits

**Pack Tactics.** The hoplite has advantage on an attack roll against a creature if at least one of the hoplite's allies is within 5 feet of the hoplite and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The hoplite makes two scimitar attacks or two longbow attacks.

**Scimitar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage plus 10 (3d6) poison damage.

**Longbow.** Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 10 (3d6) poison damage.


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