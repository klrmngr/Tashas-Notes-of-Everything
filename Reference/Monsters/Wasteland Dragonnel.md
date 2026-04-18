---
type: pc
race: "Dragon"
class:
 - "Wasteland Dragonnel"
subClass:
 - "CR 3"
cover: "Wasteland Dragonnel.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/large
  - cr/3
  - source/dsotdq
---
###### Wasteland Dragonnel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Wasteland Dragonnel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Dragon |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 65 (10d10 + 10) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 12 | 8 | 13 | 10 |
| **Mod** | +3 | +3 | +1 | -1 | +1 | +0 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 13
**Languages:** understands Common and Draconic but can't speak
**Skills:** Perception +3
**Damage Resistances:** acid

---

### Traits

**Flyby.** The dragonnel doesn't provoke opportunity attacks when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The dragonnel makes two Rend attacks.

**Rend.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) slashing damage.

**Acid Spit.** Ranged Weapon Attack: +5 to hit, range 60 ft., one target. *Hit:* 20 (5d6 + 3) acid damage.


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