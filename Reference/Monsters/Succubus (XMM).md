---
type: pc
race: "Fiend"
class:
 - "Succubus"
subClass:
 - "CR 4"
cover: "Succubus.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/4
  - source/xmm
---
###### Succubus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Succubus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Fiend |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 71 (13d8 + 13) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 13 | 15 | 12 | 20 |
| **Mod** | -1 | +3 | +1 | +2 | +1 | +5 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 15
**Languages:** Abyssal, Common, Infernal; telepathy 60 ft.
**Skills:** Deception +9, Insight +5, Perception +5, Persuasion +9, Stealth +7
**Damage Resistances:** cold; fire; poison; psychic

---

### Traits

**Incubus Form.** When the succubus finishes a Long Rest, it can shape-shift into an Incubus, using that stat block instead of this one.


---

### Actions

**Multiattack.** The succubus makes one Fiendish Touch attack and uses Charm or Draining Kiss.

**Fiendish Touch.** m +7, reach 5 ft. *Hit:* 16 (2d10 + 5) Psychic damage.

**Charm.** The succubus casts Dominate Person (level 8 version), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 15).

**Draining Kiss.** con DC 15, one creature Charmed by the succubus within 5 feet.  13 (3d8) Psychic damage.  Half damage.  The target's Hit Point maximum decreases by an amount equal to the damage taken.


---

### Bonus Actions

**Shape-Shift.** The succubus shape-shifts to resemble a Medium or Small Humanoid or back into its true form. Its game statistics are the same in each form, except its Fly Speed is available only in its true form. Any equipment it's wearing or carrying isn't transformed.


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