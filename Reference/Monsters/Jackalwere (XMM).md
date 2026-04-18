---
type: pc
race: "Fiend"
class:
 - "Jackalwere"
subClass:
 - "CR 1/2"
cover: "Jackalwere.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/small
  - cr/1-2
  - source/xmm
---
###### Jackalwere
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Jackalwere.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Fiend |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 18 (4d6 + 4) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 12 | 13 | 11 | 10 |
| **Mod** | +0 | +2 | +1 | +1 | +0 | +0 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 90 ft., passive Perception 14
**Languages:** Common
**Skills:** Deception +4, Perception +4, Stealth +4

---

### Traits

**Pack Tactics.** The jackalwere has Advantage on an attack roll against a creature if at least one of the jackalwere's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Multiattack.** The jackalwere makes two Rend or Slam attacks.

**Rend (Jackal or Hybrid Form Only).** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage.

**Slam (Human or Hybrid Form Only).** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Bludgeoning damage.

**Sleep Gaze (Recharge 5–6).** wis DC 10, one creature the jackalwere can see within 30 feet (Constructs and Undead succeed automatically).  The target has the Unconscious condition for 10 minutes or until it takes damage or a creature within 5 feet of it takes an action to wake it.  The target is immune to this jackalwere's Sleep Gaze for 24 hours.


---

### Bonus Actions

**Shape-Shift.** The jackalwere shape-shifts into a Medium human or a Medium jackal-humanoid hybrid, or it returns to its true form (that of a Small jackal). Other than its size, its game statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.


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