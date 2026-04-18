---
type: pc
race: "Humanoid (elf)"
class:
 - "Iriad"
subClass:
 - "CR —"
cover: "Iriad.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/dsotdq
---
###### Iriad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Dragonlance: Shadow of the Dragon Queen
___

> [!infobox|no-t right]
> ![[Iriad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Dragonlance: Shadow of the Dragon Queen |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 12 | 11 | 13 | 11 |
| **Mod** | +0 | +3 | +1 | +0 | +1 | +0 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish
**Saving Throws:** Dex +4
**Skills:** Acrobatics +5, Athletics +2, Investigation +2, Nature +2, Perception +5, Stealth +5, Survival +3

---

### Traits

**Bonus Proficiencies.** Iriad is proficient with simple weapons, light armor, cartographer's tools, and woodcarver's tools.

**Fey Ancestry.** Iriad has advantage on saving throws made to avoid or end the charmed condition on herself, and magic can't put her to sleep.


---

### Actions

**Poison Dagger.** Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 3 (1d6) poison damage.


---

### Bonus Actions

**Helpful.** Iriad takes the Help action.


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