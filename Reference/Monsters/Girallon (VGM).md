---
type: pc
race: "Monstrosity"
class:
 - "Girallon"
subClass:
 - "CR 4"
cover: "Girallon.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/4
  - source/vgm
---
###### Girallon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Girallon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 16 | 16 | 5 | 12 | 7 |
| **Mod** | +4 | +3 | +3 | -3 | +1 | -2 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +5

---

### Traits

**Aggressive.** As a bonus action, the girallon can move up to its speed toward a hostile creature that it can see.

**Keen Smell.** The girallon has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** The girallon makes five attacks: one with its bite and four with its claws.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one creature. *Hit:* 7 (1d6 + 4) piercing damage.

**Claw.** Melee Weapon Attack: +6 to hit. reach 10 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.


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