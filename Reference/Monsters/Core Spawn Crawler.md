---
type: pc
race: "Aberration"
class:
 - "Core Spawn Crawler"
subClass:
 - "CR 1"
cover: "Core Spawn Crawler.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/1
  - source/egw
---
###### Core Spawn Crawler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Core Spawn Crawler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 21 (6d6) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 14 | 10 | 9 | 12 | 6 |
| **Mod** | -2 | +2 | +0 | -1 | +1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft. (blind beyond this radius), tremorsense 60 ft., passive Perception 15
**Languages:** understands Deep Speech but can't speak
**Skills:** Perception +5
**Damage Immunities:** psychic
**Condition Immunities:** blinded

---

### Traits

**Pack Tactics.** The crawler has advantage on an attack roll against a creature if at least one of the crawler's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The crawler makes four attacks: one with its bite, two with its claws, and one with its tail.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage and the target must succeed on a DC 11 Wisdom saving throw or become frightened until the start of the crawler's next turn.

**Claws.** Melee Weapon Attack: +4 to hit, reach 15 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

**Tail.** Melee Weapon Attack: +4 to hit, reach 15 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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