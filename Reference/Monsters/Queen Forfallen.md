---
type: pc
race: "Construct"
class:
 - "Queen Forfallen"
subClass:
 - "CR 10"
cover: "Queen Forfallen.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/10
  - source/fraif
---
###### Queen Forfallen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Queen Forfallen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 153 (18d8 + 72) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 19 | 15 | 17 | 18 |
| **Mod** | +5 | +2 | +4 | +2 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common
**Saving Throws:** Wis +7
**Skills:** Athletics +9, Insight +7, Perception +7
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; petrified; poisoned

---

### Traits

**Inspiring Presence.** Creatures of Forfallen's choice (excluding herself) in a 30-foot Emanation originating from her have Advantage on attack rolls. She can't use this trait if she has the Incapacitated condition.

**Magic Resistance.** Forfallen has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** Forfallen makes three attacks, using Greataxe or Handaxe in any combination.

**Greataxe.** m +9, reach 5 ft. *Hit:* 18 (2d12 + 5) Slashing damage, and the target has the Poisoned condition until the end of its next turn.

**Handaxe.** m,r +9, reach 5 ft. or range 20/60 ft. *Hit:* 22 (5d6 + 5) Slashing damage.


---

### Bonus Actions

**Rust's Grip.** con DC 16, one creature Forfallen can see within 20 feet. The target has Disadvantage on this save if it has the Poisoned condition. 1 The target has the Restrained condition and repeats the save at the end of its next turn if it's still Restrained, ending the effect on itself on a success. 2 The target has the Petrified condition instead of the Restrained condition, becoming a statue of rusted iron.


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