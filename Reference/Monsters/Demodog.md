---
type: pc
race: "Fiend (demon)"
class:
 - "Demodog"
subClass:
 - "CR 1"
cover: "Demodog.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/small
  - cr/1
  - source/wtthc
---
###### Demodog
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Demodog.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Fiend (demon) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 27 (6d6 + 6) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 15 | 12 | 6 | 12 | 6 |
| **Mod** | +3 | +2 | +1 | -2 | +1 | -2 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 11
**Languages:** —
**Skills:** Stealth +4
**Damage Resistances:** cold; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Pack Tactics.** The demodog has Advantage on an attack roll against a creature if at least one of the demodog's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.


---

### Actions

**Bite.** m +5, reach 5 ft. *Hit:* 8 (1d10 + 3) Piercing damage. If the target is a Medium or smaller creature, it has the Prone condition.


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