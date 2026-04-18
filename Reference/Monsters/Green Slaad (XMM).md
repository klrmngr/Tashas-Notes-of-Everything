---
type: pc
race: "Aberration"
class:
 - "Green Slaad"
subClass:
 - "CR 8"
cover: "Green Slaad.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/8
  - source/xmm
---
###### Green Slaad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Green Slaad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 144 (17d10 + 51) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 15 | 16 | 11 | 8 | 18 |
| **Mod** | +3 | +2 | +3 | +0 | -1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., Darkvision 60 ft., passive Perception 12
**Languages:** Common, Slaad; telepathy 60 ft.
**Skills:** Arcana +3, Perception +2
**Damage Resistances:** acid; cold; fire; lightning; thunder

---

### Traits

**Magic Resistance.** The slaad has Advantage on saving throws against spells and other magical effects.

**Regeneration.** The slaad regains 10 Hit Points at the start of each of its turns if it has at least 1 Hit Point.


---

### Actions

**Multiattack.** The slaad makes three Chaos Staff attacks.

**Chaos Staff.** m,r +7, reach 10 ft. or range 60 ft. *Hit:* 8 (1d8 + 4) Force damage. Until the start of the slaad's next turn, the target has a condition determined by rolling 1d4: on a 1, Charmed; on a 2, Frightened; on a 3, Poisoned; or on a 4, Incapacitated.


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