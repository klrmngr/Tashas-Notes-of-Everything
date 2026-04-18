---
type: pc
race: "Monstrosity"
class:
 - "Giant Slug"
subClass:
 - "CR 3"
cover: "Giant Slug.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/ttp
---
###### Giant Slug
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: TTP
___

> [!infobox|no-t right]
> ![[Giant Slug.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 66 (6d10 + 18) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | TTP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 13 | 16 | 1 | 12 | 5 |
| **Mod** | +2 | +1 | +3 | -5 | +1 | -3 |

**Speed:** 10 ft., climb 10 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Abyssal, Aquan, Common
**Skills:** Perception +3

---

### Traits

**Keen Smell.** The slug has advantage on Wisdom (Perception) checks that rely on smell.

**Spider Climb.** The slug can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.


---

### Actions

**Multiattack.** The slug makes two attacks: one with its tentacles and one with its bite.

**Tentacles.** Melee Weapon Attack: +8 to hit, reach 10 ft., one creature. *Hit:* 4 (1d4 + 2) poison damage, and the target must succeed on a DC 13 Constitution saving throw or be poisoned for 1 minute. Until this poison ends, the target is paralyzed. The target can repeat the saving throw at the end of each of its turns, ending the poison on itself on a success.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) piercing damage.


---

### Reactions

**Animate Tentacle.** When the slug takes damage in this cave (3), it can use its reaction to animate one of the tentacles of the kraken statue and cause it to   make a melee weapon attack (+3 to hit) against one creature within 20 feet of the statue that the slug can see. The tentacle deals 8 (1d8 + 4) bludgeoning damage on a hit.


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