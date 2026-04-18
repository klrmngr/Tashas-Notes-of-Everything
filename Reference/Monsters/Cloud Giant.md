---
type: pc
race: "Giant"
class:
 - "Cloud Giant"
subClass:
 - "CR 9"
cover: "Cloud Giant.png"
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
###### Cloud Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Cloud Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Good or Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 200 (16d12 + 96) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 27 | 10 | 22 | 12 | 16 | 16 |
| **Mod** | +8 | +0 | +6 | +1 | +3 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Common, Giant
**Saving Throws:** Con +10, Wis +7, Cha +7
**Skills:** Insight +7, Perception +7

---

### Traits

**Keen Smell.** The giant has advantage on Wisdom (Perception) checks that rely on smell.


---

### Actions

**Multiattack.** The giant makes two morningstar attacks.

**Morningstar.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 21 (3d8 + 8) piercing damage.

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