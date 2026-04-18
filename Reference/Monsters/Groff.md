---
type: pc
race: "Plant"
class:
 - "Groff"
subClass:
 - "CR 4"
cover: "Groff.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/4
  - source/scc
---
###### Groff
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Strixhaven: A Curriculum of Chaos
___

> [!infobox|no-t right]
> ![[Groff.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Strixhaven: A Curriculum of Chaos |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 17 | 4 | 13 | 7 |
| **Mod** | +5 | +0 | +3 | -3 | +1 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** —
**Skills:** Perception +3, Stealth +4

---

### Traits

**False Appearance.** If the groff is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the groff move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the groff isn't an ordinary moss-covered bog patch.

**Hold Breath.** The groff can hold its breath for up to 1 hour.


---

### Actions

**Multiattack.** The groff makes one Bite attack and one Swamp Claw attack.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage.

**Swamp Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage. If the target is a Medium or smaller creature, it must succeed on a DC 15 Strength saving throw or become engulfed by the groff. While engulfed, the target can't breathe, is restrained, and takes 10 (3d6) poison damage at the start of each of its turns. When the groff moves, the engulfed target moves with it. The groff can have only one target engulfed at a time.
An engulfed target can repeat the saving throw at the end of its turns. On a success, the target escapes and enters the nearest unoccupied space.


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