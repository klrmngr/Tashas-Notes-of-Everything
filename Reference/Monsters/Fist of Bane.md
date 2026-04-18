---
type: pc
race: "Humanoid (human)"
class:
 - "Fist of Bane"
subClass:
 - "CR 1/2"
cover: "Fist of Bane.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/bgdia
---
###### Fist of Bane
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Fist of Bane.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (chain mail, shield) |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 13 | 10 | 12 | 11 |
| **Mod** | +3 | +0 | +1 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common
**Condition Immunities:** frightened

---

### Traits

**Tactical Discipline.** The fist of Bane has advantage on all ability checks and saving throws made during combat.


---

### Actions

**Mace.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage.

**Longbow.** Ranged Weapon Attack: +2 to hit, range 150/600 ft., one target. *Hit:* 4 (1d8) piercing damage.


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