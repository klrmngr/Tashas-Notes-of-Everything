---
type: pc
race: "Fey"
class:
 - "Quickling"
subClass:
 - "CR 1"
cover: "Quickling.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/tiny
  - cr/1
  - source/vgm
---
###### Quickling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Quickling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Fey |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 10 (3d4 + 3) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 23 | 13 | 10 | 12 | 7 |
| **Mod** | -3 | +6 | +1 | +0 | +1 | -2 |

**Speed:** 120 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Common, Sylvan
**Skills:** Acrobatics +8, Perception +5, Sleight Of Hand +8, Stealth +8

---

### Traits

**Blurred Movement.** Attack rolls against the quickling have disadvantage unless the quickling is incapacitated or restrained.

**Evasion.** If the quickling is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.


---

### Actions

**Multiattack.** The quickling makes three dagger attacks.

**Dagger.** Melee or Ranged Weapon Attack: +8 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 8 (1d4 + 6) piercing damage.


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