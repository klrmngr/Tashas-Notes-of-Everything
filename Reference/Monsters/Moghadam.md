---
type: pc
race: "Humanoid (human)"
class:
 - "Moghadam"
subClass:
 - "CR 12"
cover: "Moghadam.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/12
  - source/imr
---
###### Moghadam
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: IMR
___

> [!infobox|no-t right]
> ![[Moghadam.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (breastplate) |
> | :FasHeart: HP | 104 (19d8 + 19) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | IMR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 13 | 19 | 16 | 16 |
| **Mod** | +0 | +1 | +1 | +4 | +3 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Abyssal, Common, Dwarvish, Infernal, Undercommon
**Saving Throws:** Con +5, Int +8, Wis +7
**Skills:** Arcana +8, Insight +7, Medicine +7

---

### Traits

**Special Equipment.** Moghadam wields Ruinblade (see appendix C).

**Artificial Mind.** Moghadam can manifest an artificial mind as a floating spectral image of a demilich's jeweled skull. Moghadam can communicate telepathically with this mind, send it up to 300 feet away from him, and see and hear through it.

**Infoportation (1/Day).** Moghadam can teleport himself into an unoccupied space next to his artificial mind.


---

### Actions

**Ruinblade.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage.

**Blight (1/Day).** While wielding Ruinblade, Moghadam can cast the blight spell (DC 15).

**Disintegrate (1/7 Days).** While wielding Ruinblade, Moghadam can cast the disintegrate spell against any nonmagical object or creation of magical force.

**Information Overload (Recharge 5–6).** Moghadam overloads the thoughts of one creature within 5 feet of either himself or his artificial mind. The target must succeed on a DC 16 Intelligence saving throw or take 22 (4d8 + 4) psychic damage, and the next attack roll made against the target before the end of Moghadam's next turn has advantage.


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