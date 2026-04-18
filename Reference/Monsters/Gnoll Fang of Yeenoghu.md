---
type: pc
race: "Fiend (gnoll)"
class:
 - "Gnoll Fang of Yeenoghu"
subClass:
 - "CR 4"
cover: "Gnoll Fang of Yeenoghu.png"
campaign:
locations:
tags:
  - race/gnoll
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/mm
---
###### Gnoll Fang of Yeenoghu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Gnoll Fang of Yeenoghu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Fiend (gnoll) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 15 | 10 | 11 | 13 |
| **Mod** | +3 | +2 | +2 | +0 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Abyssal, Gnoll
**Saving Throws:** Con +4, Wis +2, Cha +3

---

### Traits

**Rampage.** When the gnoll reduces a creature to 0 hit points with a melee attack on its turn, the gnoll can take a bonus action to move up to half its speed and make a bite attack.


---

### Actions

**Multiattack.** The gnoll makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 6 (1d6 + 3) piercing damage, and the target must succeed on a DC 12 Constitution saving throw or take 7 (2d6) poison damage.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage.


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