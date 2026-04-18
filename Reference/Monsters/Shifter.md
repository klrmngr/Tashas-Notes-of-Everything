---
type: pc
race: "Humanoid (shifter)"
class:
 - "Shifter"
subClass:
 - "CR 1/2"
cover: "Shifter.png"
campaign:
locations:
tags:
  - race/shifter
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/erlw
---
###### Shifter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Shifter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (shifter) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 19 (3d8 + 6) |
> | :FasUserGroup: Race | Humanoid (shifter) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 14 | 11 | 15 | 10 |
| **Mod** | +1 | +3 | +2 | +0 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common
**Skills:** Acrobatics +5, Insight +4, Nature +2, Perception +4

---

### Traits

**Shifting (Recharges after a Short or Long Rest).** As a bonus action, the shifter takes on a more bestial form for 1 minute or until it dies. The shifter gains 5 temporary hit points. It can make a bite attack when it activates this trait and also as a bonus action on each of its turns while in its bestial form.


---

### Actions

**Shortsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 5 (1d4 + 3) piercing damage.


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