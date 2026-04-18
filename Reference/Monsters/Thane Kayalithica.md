---
type: pc
race: "Giant"
class:
 - "Thane Kayalithica"
subClass:
 - "CR 7"
cover: "Thane Kayalithica.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/7
  - source/skt
---
###### Thane Kayalithica
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Thane Kayalithica.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 170 (11d12 + 55) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 15 | 20 | 10 | 12 | 14 |
| **Mod** | +6 | +2 | +5 | +0 | +1 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Giant
**Saving Throws:** Dex +5, Con +8, Wis +4
**Skills:** Athletics +12, Perception +4

---

### Traits

**Stone Camouflage.** The giant has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.

**Olach Morrah.** The giant meditates for 1 hour, during which time it can do nothing else. At the end of the hour, provided the giant's meditation has been uninterrupted, it becomes petrified for 8 hours. At the end of this time, the giant is no longer petrified and gains tremorsense out to a range of 30 feet, as well as a measure of innate spellcasting ability for the next 24 hours.


---

### Actions

**Fling.** The giant tries to throw a Small or Medium creature within 10 feet of it. The target must succeed on a DC 17 Dexterity saving throw or be hurled up to 60 feet horizontally in a direction of the giant's choice. and land prone, taking 1d6 bludgeoning damage for every 10 feet it was thrown.

**Rolling Rock.** The giant sends a rock tumbling along the ground in a 30-foot line that is 5 feet wide. Each creature in that line must make a DC 17 Dexterity saving throw, taking 22 (3d10 + 6) bludgeoning damage and falling prone on a failed save

**Multiattack.** The giant makes two adamantine greatclub attacks.

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