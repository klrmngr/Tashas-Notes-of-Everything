---
type: pc
race: "Monstrosity"
class:
 - "Amphisbaena"
subClass:
 - "CR 1/2"
cover: "Amphisbaena.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1-2
  - source/gos
---
###### Amphisbaena
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Amphisbaena.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 12 | 3 | 10 | 3 |
| **Mod** | +2 | +4 | +1 | -4 | +0 | -4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., passive Perception 12
**Languages:** —
**Skills:** Perception +2

---

### Traits

**Two Heads.** The amphisbaena has advantage on Wisdom (Perception) checks and on saving throws against being blinded, charmed, deafened, frightened, stunned, and knocked unconscious.


---

### Actions

**Multiattack.** The amphisbaena makes two bite attacks.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage, and the target must make a DC 11 Constitution saving throw, taking 3 (1d6) poison damage on a failed save, or half as much damage on a successful one.


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