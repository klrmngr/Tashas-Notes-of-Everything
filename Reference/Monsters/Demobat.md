---
type: pc
race: "Fiend (demon)"
class:
 - "Demobat"
subClass:
 - "CR 1/2"
cover: "Demobat.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/tiny
  - cr/1-2
  - source/wtthc
---
###### Demobat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Demobat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Tiny Fiend (demon) |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 21 (6d4 + 6) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 16 | 12 | 2 | 10 | 6 |
| **Mod** | -3 | +3 | +1 | -4 | +0 | -2 |

**Speed:** 10 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** cold; lightning
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Actions

**Bite.** m +5 (with Advantage if the target is Grappled by a Demobat), reach 5 ft.  *Hit:* 10 (2d6 + 3) Piercing damage.

**Tentacles.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing damage. If the target is a Medium or smaller creature, the target has the Grappled condition (escape DC 13) from all four tentacles.


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