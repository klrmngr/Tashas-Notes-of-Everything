---
type: pc
race: "Giant"
class:
 - "Zephyros"
subClass:
 - "CR 13"
cover: "Zephyros.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/13
  - source/skt
---
###### Zephyros
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Zephyros.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 22 | 18 | 16 | 16 |
| **Mod** | +8 | +0 | +6 | +4 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common, Giant
**Saving Throws:** Con +11, Wis +8, Cha +8
**Skills:** Insight +8, Perception +8

---

### Traits

**Keen Smell.** Zephyros has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Fling.** Zephyros tries to throw a Small or Medium creature within 10 feet of it. The target must succeed on a DC 20 Dexterity saving throw or be hurled up to 60 feet horizontally in a direction of Zephyros's choice and land prone, taking 1d8 bludgeoning damage for every 10 feet it was thrown.

**Wind Aura.** A magical aura of wind surrounds Zephyros. The aura is a 10-foot-radius sphere that lasts as long as he maintains concentration on it (as if concentrating on a spell). While the aura is in effect, Zephyros gains a +2 bonus to his AC against ranged weapon attacks, and all open flames within the aura are extinguished unless they are magical.

**Multiattack.** Zephyros makes two staff attacks.

**Staff of the Magi.** Melee Weapon Attack: +15 to hit, reach 10 ft., one target. *Hit:* 20 (3d6 + 10) bludgeoning damage, or 23 (3d8 + 10) bludgeoning damage if used with two hands. This damage is considered magical..

**Rock.** Ranged Weapon Attack: +12 to hit, range 60/240 ft., one target. *Hit:* 30 (4d10 + 8) bludgeoning damage.


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