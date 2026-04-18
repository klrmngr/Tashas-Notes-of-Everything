---
type: pc
race: "Monstrosity (lycanthrope)"
class:
 - "Wereboar"
subClass:
 - "CR 4"
cover: "Wereboar.png"
campaign:
locations:
tags:
  - race/lycanthrope
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/4
  - source/xmm
---
###### Wereboar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Wereboar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Monstrosity (lycanthrope) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Monstrosity (lycanthrope) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 15 | 10 | 11 | 8 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common (can't speak in boar form)
**Skills:** Perception +2

---

### Actions

**Multiattack.** The wereboar makes two attacks, using Javelin or Tusk in any combination. It can replace one attack with a Gore attack.

**Gore (Boar or Hybrid Form Only).** m +5, reach 5 ft. *Hit:* 12 (2d8 + 3) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. con DC 12.  The target is cursed. If the cursed target drops to 0 Hit Points, it instead becomes a Wereboar under the DM's control and has 10 Hit Points.  The target is immune to this wereboar's curse for 24 hours.

**Javelin (Humanoid or Hybrid Form Only).** m,r +5, reach 5 ft. or range 30/120 ft. *Hit:* 13 (3d6 + 3) Piercing damage.

**Tusk (Boar or Hybrid Form Only).** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Piercing damage. If the target is a Medium or smaller creature and the wereboar moved 20+ feet straight toward it immediately before the hit, the target takes an extra 7 (2d6) Piercing damage and has the Prone condition.


---

### Bonus Actions

**Shape-Shift.** The wereboar shape-shifts into a Medium boar-humanoid hybrid or a Small boar, or it returns to its true humanoid form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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