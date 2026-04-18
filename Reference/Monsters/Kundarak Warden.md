---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Kundarak Warden"
subClass:
 - "CR 5"
cover: "Kundarak Warden.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/5
  - source/efa
---
###### Kundarak Warden
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Kundarak Warden.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 16 | 17 | 13 | 10 |
| **Mod** | +2 | +1 | +3 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 11
**Languages:** Common, Dwarvish
**Saving Throws:** Str +5, Dex +4, Con +6, Int +6, Wis +4

---

### Traits

**Magic Resistance.** The warden has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The warden makes two Arcane Whip attacks. It can replace one attack with a use of Shackling Glyph if available.

**Arcane Whip.** m +6, reach 10 ft. *Hit:* 13 (3d6 + 3) Force damage, and if the target is a Medium or smaller creature, it has the Prone condition. If the target already has the Prone condition, the attack deals an extra 7 (2d6) Force damage.

**Shackling Glyph (Recharge 6).** str DC 14, one creature the warden can see within 60 feet.  The creature has the Grappled condition (escape DC 14). While Grappled, the creature has the Restrained condition.


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