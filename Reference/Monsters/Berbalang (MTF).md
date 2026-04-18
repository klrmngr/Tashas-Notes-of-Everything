---
type: pc
race: "Aberration"
class:
 - "Berbalang"
subClass:
 - "CR 2"
cover: "Berbalang.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/2
  - source/mtf
---
###### Berbalang
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Berbalang.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 38 (11d8 - 11) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 16 | 9 | 17 | 11 | 10 |
| **Mod** | -1 | +3 | -1 | +3 | +0 | +0 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 12
**Languages:** all but rarely speaks
**Saving Throws:** Dex +5, Int +5
**Skills:** Arcana +5, History +5, Insight +2, Perception +2, Religion +5

---

### Traits

**Spectral Duplicate (Recharges after a Short or Long Rest).** As a bonus action, the berbalang creates one spectral duplicate of itself in an unoccupied space it can see within 60 feet of it. While the duplicate exists, the berbalang is unconscious. A berbalang can have only one duplicate at a time. The duplicate disappears when it or the berbalang drops to 0 hit points or when the berbalang dismisses it (no action required).
The duplicate has the same statistics and knowledge as the berbalang, and everything experienced by the duplicate is known by the berbalang. All damage dealt by the duplicate's attacks is psychic damage.


---

### Actions

**Multiattack.** The berbalang makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage.

**Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (2d4 + 3) slashing damage.


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