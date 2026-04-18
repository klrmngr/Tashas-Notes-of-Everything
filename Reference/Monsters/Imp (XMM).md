---
type: pc
race: "Fiend (devil)"
class:
 - "Imp"
subClass:
 - "CR 1"
cover: "Imp.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/tiny
  - cr/1
  - source/xmm
---
###### Imp
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Imp.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Fiend (devil) |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 21 (6d4 + 6) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 17 | 13 | 11 | 12 | 14 |
| **Mod** | -2 | +3 | +1 | +0 | +1 | +2 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft. (unimpeded by magical Darkness), passive Perception 11
**Languages:** Common, Infernal
**Skills:** Deception +4, Insight +3, Stealth +5
**Damage Resistances:** cold
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The imp has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Sting.** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing damage plus 7 (2d6) Poison damage.

**Shape-Shift.** The imp shape-shifts to resemble a rat (Speed 20 ft.), a raven (20 ft., Fly 60 ft.), or a spider (20 ft., Climb 20 ft.), or it returns to its true form. Its statistics are the same in each form, except for its Speed. Any equipment it is wearing or carrying isn't transformed.


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