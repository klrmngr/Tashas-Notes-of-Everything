---
type: pc
race: "Aberration"
class:
 - "Death Slaad"
subClass:
 - "CR 10"
cover: "Death Slaad.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/10
  - source/xmm
---
###### Death Slaad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Death Slaad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 178 (21d8 + 84) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 19 | 15 | 10 | 19 |
| **Mod** | +5 | +2 | +4 | +2 | +0 | +4 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., Darkvision 60 ft., passive Perception 18
**Languages:** Common, Slaad; telepathy 60 ft.
**Skills:** Arcana +6, Perception +8
**Damage Resistances:** acid; cold; fire; lightning; thunder

---

### Traits

**Magic Resistance.** The slaad has Advantage on saving throws against spells and other magical effects.

**Regeneration.** The slaad regains 10 Hit Points at the start of each of its turns if it has at least 1 Hit Point.


---

### Actions

**Multiattack.** The slaad makes two Chaos Blade attacks.

**Chaos Blade.** m +9, reach 10 ft. *Hit:* 11 (1d12 + 5) Slashing damage plus 10 (3d6) Necrotic damage. Until the start of the slaad's next turn, the target has a condition determined by rolling 1d4: on a 1, Charmed; on a 2, Frightened; on a 3, Poisoned; or on a 4, Incapacitated.


---

### Bonus Actions

**Shape-Shift.** The slaad shape-shifts into a Small or Medium Humanoid, or it returns to its true form. Other than its size, its game statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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