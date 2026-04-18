---
type: pc
race: "Beast"
class:
 - "Giant Owl"
subClass:
 - "CR 1/4"
cover: "Giant Owl.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/1-4
  - source/mm
---
###### Giant Owl
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Giant Owl.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 19 (3d10 + 3) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 15 | 12 | 8 | 13 | 10 |
| **Mod** | +1 | +2 | +1 | -1 | +1 | +0 |

**Speed:** 5 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Giant Owl, understands Common, Elvish, and Sylvan but can't speak them
**Skills:** Perception +5, Stealth +4

---

### Traits

**Flyby.** The owl doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Keen Hearing and Sight.** The owl has advantage on Wisdom (Perception) checks that rely on hearing or sight.


---

### Actions

**Talons.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 8 (2d6 + 1) slashing damage.


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