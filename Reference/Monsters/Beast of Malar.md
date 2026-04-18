---
type: pc
race: "Monstrosity"
class:
 - "Beast of Malar"
subClass:
 - "CR 11"
cover: "Beast of Malar.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/11
  - source/fraif
---
###### Beast of Malar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Beast of Malar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 168 (16d8 + 96) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 16 | 23 | 10 | 14 | 12 |
| **Mod** | +5 | +3 | +6 | +0 | +2 | +1 |

**Speed:** 50 ft., burrow 40 ft. ((land form only)), fly 60 ft. ((sky form only)), swim 40 ft. ((sea form only)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 20
**Languages:** understands Common but can't speak
**Saving Throws:** Str +9
**Skills:** Perception +10, Stealth +7
**Condition Immunities:** charmed; frightened

---

### Traits

**Amphibious (Sea Form Only).** The beast breathes air and water.

**Divine Immortality.** If the beast dies, its body dissolves into black goo, and it gains a new body after 1d10 days, reviving with all its Hit Points in a place of Malar's choosing.

**Legendary Resistance (3/Day).** If the beast fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The beast has Advantage on saving throws against spells and other magical effects.

**Regeneration.** The beast regains 20 Hit Points at the start of its turn. If the beast takes Radiant damage or damage from a Critical Hit, this trait doesn't function at the start of the beast's next turn. The beast dies only if it starts its turn with 0 Hit Points and doesn't regenerate.


---

### Actions

**Multiattack.** The beast makes three attacks, using Bite or Claws in any combination.

**Bite.** m +9, reach 5 ft. *Hit:* 23 (4d8 + 5) Piercing damage.

**Claws (Land or Sky Form Only).** m +9, reach 5 ft. *Hit:* 18 (3d8 + 5) Slashing damage. If the target is Large or smaller, it has the Prone condition.


---

### Bonus Actions

**Recuperative Shape-Shift.** The beast shape-shifts into its land form, sea form, or sky form and regains 9 (2d8) Hit Points. Its game statistics are the same in each form, except where noted. Any equipment it is wearing or carrying isn't transformed.


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