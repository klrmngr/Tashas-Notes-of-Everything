---
type: pc
race: "Giant"
class:
 - "Stone Giant"
subClass:
 - "CR 7"
cover: "Stone Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/7
  - source/mm
---
###### Stone Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Stone Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 126 (11d12 + 55) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 15 | 20 | 10 | 12 | 9 |
| **Mod** | +6 | +2 | +5 | +0 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Giant
**Saving Throws:** Dex +5, Con +8, Wis +4
**Skills:** Athletics +12, Perception +4

---

### Traits

**Stone Camouflage.** The giant has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.


---

### Actions

**Multiattack.** The giant makes two greatclub attacks.

**Greatclub.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed on a DC 17 Strength saving throw or be knocked prone.


---

### Reactions

**Rock Catching.** If a rock or similar object is hurled at the giant, the giant can, with a successful DC 10 Dexterity saving throw, catch the missile and take no bludgeoning damage from it.


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