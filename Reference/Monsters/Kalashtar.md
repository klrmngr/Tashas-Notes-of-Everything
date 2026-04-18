---
type: pc
race: "Humanoid (kalashtar)"
class:
 - "Kalashtar"
subClass:
 - "CR 1/4"
cover: "Kalashtar.png"
campaign:
locations:
tags:
  - race/kalashtar
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-4
  - source/erlw
---
###### Kalashtar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Kalashtar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Humanoid (kalashtar) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Humanoid (kalashtar) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 12 | 13 | 15 | 15 |
| **Mod** | +1 | +2 | +1 | +1 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, telepathy 20 ft.
**Skills:** Acrobatics +4, Insight +4, Persuasion +6
**Damage Resistances:** psychic

---

### Traits

**Dual Mind.** The kalashtar has advantage on Wisdom saving throws.


---

### Actions

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.

**Mind Thrust.** The kalashtar targets a creature it can see within 30 feet of it. The target must succeed on a DC 12 Wisdom saving throw or take 11 (2d10) psychic damage.


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