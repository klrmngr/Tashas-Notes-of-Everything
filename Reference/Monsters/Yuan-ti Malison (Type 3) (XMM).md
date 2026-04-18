---
type: pc
race: "Monstrosity"
class:
 - "Yuan-ti Malison (Type 3)"
subClass:
 - "CR 3"
cover: "Yuan-ti Malison (Type 3).png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/xmm
---
###### Yuan-ti Malison (Type 3)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Yuan-ti Malison (Type 3).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 14 | 16 | 12 |
| **Mod** | +3 | +2 | +1 | +2 | +3 | +1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Abyssal, Common, Draconic
**Skills:** Stealth +4 (+6 while in snake form)
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The yuan-ti has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The yuan-ti makes two Poison Burst attacks, and it can use Spellcasting to cast Suggestion if available.

**Poison Burst (Yuan-ti Form Only).** m,r +5, reach 5 ft. or range 120 ft. *Hit:* 12 (2d8 + 3) Poison damage.

**Constrict.** str DC 13, one Medium or smaller creature within 5 feet.  21 (4d8 + 3) Bludgeoning damage. The target has the Grappled condition (escape DC 13), and it has the Restrained condition until the grapple ends.


---

### Bonus Actions

**Shape-Shift.** The yuan-ti shape-shifts into a Medium snake or returns to its true form. If it dies, it stays in its current form. The yuan-ti's game statistics are the same in each form, except where noted. Any equipment it is wearing or carrying isn't transformed.


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