---
type: pc
race: "Humanoid (gnoll)"
class:
 - "Gnoll"
subClass:
 - "CR 1/2"
cover: "Gnoll.png"
campaign:
locations:
tags:
  - race/gnoll
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/mm
---
###### Gnoll
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Gnoll.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (hide armor, shield) |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (gnoll) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 11 | 6 | 10 | 7 |
| **Mod** | +2 | +1 | +0 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Gnoll

---

### Traits

**Rampage.** When the gnoll reduces a creature to 0 hit points with a melee attack on its turn, the gnoll can take a bonus action to move up to half its speed and make a bite attack.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage.

**Spear.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing damage if used with two hands to make a melee attack.

**Longbow.** Ranged Weapon Attack: +3 to hit, range 150/600 ft., one target. *Hit:* 5 (1d8 + 1) piercing damage.


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