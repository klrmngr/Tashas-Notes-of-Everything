---
type: pc
race: "Undead"
class:
 - "Harrow Hawk"
subClass:
 - "CR 1"
cover: "Harrow Hawk.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/1
  - source/bmt
---
###### Harrow Hawk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Harrow Hawk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 25 (10d4) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 5 | 16 | 10 | 2 | 14 | 7 |
| **Mod** | -3 | +3 | +0 | -4 | +2 | -2 |

**Speed:** 10 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** —
**Skills:** Perception +6, Stealth +5
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Actions

**Talons.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (2d4 + 3) slashing damage plus 3 (1d6) necrotic damage.

**Plane Shift (2/Day).** The hawk casts Plane Shift on itself, requiring no spell components and using Wisdom as the spellcasting ability.


---

### Bonus Actions

**Shadow Dash.** When the hawk is in dim light or darkness, it teleports up to 30 feet to an unoccupied space it can see that is also in dim light or darkness. The hawk then has advantage on the first melee attack it makes before the end of the turn.


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