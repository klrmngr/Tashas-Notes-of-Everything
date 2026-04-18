---
type: pc
race: "Giant"
class:
 - "Frost Giant"
subClass:
 - "CR 8"
cover: "Frost Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/8
  - source/mm
---
###### Frost Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Frost Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (patchwork armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 9 | 21 | 9 | 10 | 12 |
| **Mod** | +6 | -1 | +5 | -1 | +0 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Giant
**Saving Throws:** Con +8, Wis +3, Cha +4
**Skills:** Athletics +9, Perception +3
**Damage Immunities:** cold

---

### Actions

**Multiattack.** The giant makes two greataxe attacks.

**Greataxe.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 25 (3d12 + 6) slashing damage.

**Rock.** Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage.


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