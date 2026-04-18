---
type: pc
race: "Monstrosity"
class:
 - "Egg Hunter Hatchling"
subClass:
 - "CR 2"
cover: "Egg Hunter Hatchling.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/2
  - source/ftd
---
###### Egg Hunter Hatchling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Egg Hunter Hatchling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 28 (8d4 + 8) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 13 | 1 | 10 | 5 |
| **Mod** | -1 | +3 | +1 | -5 | +0 | -3 |

**Speed:** 30 ft., burrow 10 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** —
**Saving Throws:** Dex +5, Wis +2
**Skills:** Perception +2, Stealth +7
**Condition Immunities:** frightened

---

### Traits

**Amphibious.** The egg hunter can breathe air and water.


---

### Actions

**Multiattack.** The egg hunter makes two Egg Tooth attacks.

**Egg Tooth.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage, or 17 (4d6 + 3) piercing damage if the target is an object.


---

### Bonus Actions

**Rapid Movement.** The egg hunter takes the Dash or Disengage action.


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