---
type: pc
race: "Construct"
class:
 - "Cogwork Archivist"
subClass:
 - "CR 4"
cover: "Cogwork Archivist.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/4
  - source/scc
---
###### Cogwork Archivist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Cogwork Archivist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 15 | 17 | 11 | 6 |
| **Mod** | +4 | +0 | +2 | +3 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** all
**Skills:** Arcana +5, History +5, Nature +5, Perception +2, Religion +5
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; petrified; poisoned

---

### Traits

**Magic Resistance.** The archivist has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The archivist makes two Grasping Limb attacks.

**Grasping Limb.** Melee Weapon Attack: +6 to hit, reach 15 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage, and the target is grappled (escape DC 14). The archivist can have no more than two targets grappled at a time.


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