---
type: pc
race: "Humanoid (elf)"
class:
 - "Varnyr"
subClass:
 - "CR 1/8"
cover: "Varnyr.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/cm
---
###### Varnyr
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Varnyr.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 (breastplate) |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 11 | 12 | 14 | 16 |
| **Mod** | +0 | +1 | +0 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Elvish
**Skills:** Deception +5, Insight +4, Persuasion +5

---

### Traits

**Fey Ancestry.** Varnyr has advantage on saving throws against being charmed, and magic can't put Varnyr to sleep.


---

### Actions

**Multiattack.** Varnyr makes two attacks.

**Cane.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.


---

### Reactions

**Parry.** Varnyr adds 2 to their AC against one melee attack that would hit it. To do so, Varnyr must see the attacker and be wielding a melee weapon.


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