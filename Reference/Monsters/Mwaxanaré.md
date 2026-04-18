---
type: pc
race: "Humanoid (human)"
class:
 - "Mwaxanaré"
subClass:
 - "CR 1/8"
cover: "Mwaxanaré.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/toa
---
###### Mwaxanaré
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Mwaxanaré.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 13 (3d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 10 | 11 | 13 | 12 | 16 |
| **Mod** | -2 | +0 | +0 | +1 | +1 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Auran, Common, telepathy 30 ft.
**Skills:** Deception +5, Nature +3, Persuasion +5, Religion +3

---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +2 to hit. reach 5 ft. or range 20/60 ft., one target. *Hit:* 2 (1d4) piercing damage.


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