---
type: pc
race: "Humanoid"
class:
 - "Sneak"
subClass:
 - "CR —"
cover: "Sneak.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/—
  - source/hol
---
###### Sneak
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HoL
___

> [!infobox|no-t right]
> ![[Sneak.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 (shield) |
> | :FasHeart: HP | 9 (2d6 + 2) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | HoL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 13 | 12 | 11 | 12 | 9 |
| **Mod** | -1 | +1 | +1 | +0 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** any one language (usually Common)
**Saving Throws:** Dex +3
**Skills:** Sleight Of Hand +3, Stealth +3

---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.


---

### Bonus Actions

**Disengage.** You take the Disengage action.


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