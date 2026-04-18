---
type: pc
race: "Giant"
class:
 - "Fire Giant"
subClass:
 - "CR 9"
cover: "Fire Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/9
  - source/mm
---
###### Fire Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Fire Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 162 (13d12 + 78) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 9 | 23 | 10 | 14 | 13 |
| **Mod** | +7 | -1 | +6 | +0 | +2 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Giant
**Saving Throws:** Dex +3, Con +10, Cha +5
**Skills:** Athletics +11, Perception +6
**Damage Immunities:** fire

---

### Actions

**Multiattack.** The giant makes two greatsword attacks.

**Greatsword.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 28 (6d6 + 7) slashing damage.

**Rock.** Ranged Weapon Attack: +11 to hit, range 60/240 ft., one target. *Hit:* 29 (4d10 + 7) bludgeoning damage.


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