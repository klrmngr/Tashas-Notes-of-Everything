---
type: pc
race: "Humanoid (half-orc)"
class:
 - "Yorn"
subClass:
 - "CR 1/2"
cover: "Yorn.png"
campaign:
locations:
tags:
  - race/half-orc
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/wdh
---
###### Yorn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDH
___

> [!infobox|no-t right]
> ![[Yorn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-orc) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 11 (leather armor) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Humanoid (half-orc) |
> | :FasBook: Source | WDH |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 11 | 14 | 10 | 10 | 11 |
| **Mod** | +2 | +0 | +2 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Orc
**Skills:** Intimidation +2

---

### Traits

**Pack Tactics.** The thug has advantage on an attack roll against a creature if at least one of the thug's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Relentless Endurance (1/Day).** When reduced to 0 hit points Yorn drops to 1 hit point instead.


---

### Actions

**Multiattack.** The thug makes two melee attacks.

**Mace.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 5 (1d6 + 2) bludgeoning damage.

**Heavy Crossbow.** Ranged Weapon Attack: +2 to hit, range 100/400 ft., one target. *Hit:* 5 (1d10) piercing damage.


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