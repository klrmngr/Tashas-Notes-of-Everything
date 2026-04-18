---
type: pc
race: "Dragon"
class:
 - "White Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "White Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/mm
---
###### White Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[White Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 5 | 10 | 11 |
| **Mod** | +2 | +0 | +2 | -3 | +0 | +0 |

**Speed:** 30 ft., burrow 15 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +2, Con +4, Wis +2, Cha +2
**Skills:** Perception +4, Stealth +2
**Damage Immunities:** cold

---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage plus 2 (1d4) cold damage.

**Cold Breath (Recharge 5–6).** The dragon exhales an icy blast of hail in a 15-foot cone. Each creature in that area must make a DC 12 Constitution saving throw, taking 22 (5d8) cold damage on a failed save, or half as much damage on a successful one.


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