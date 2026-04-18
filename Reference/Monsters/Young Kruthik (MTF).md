---
type: pc
race: "Monstrosity"
class:
 - "Young Kruthik"
subClass:
 - "CR 1/8"
cover: "Young Kruthik.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/1-8
  - source/mtf
---
###### Young Kruthik
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Young Kruthik.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 9 (2d6 + 2) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 13 | 4 | 10 | 6 |
| **Mod** | +1 | +3 | +1 | -3 | +0 | -2 |

**Speed:** 30 ft., burrow 10 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., tremorsense 60 ft., passive Perception 10
**Languages:** Kruthik

---

### Traits

**Keen Smell.** The kruthik has advantage on Wisdom (Perception) checks that rely on smell.

**Pack Tactics.** The kruthik has advantage on an attack roll against a creature if at least one of the kruthik's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Tunneler.** The kruthik can burrow through solid rock at half its burrowing speed and leaves a 2½-foot-diameter tunnel in its wake.


---

### Actions

**Stab.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


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