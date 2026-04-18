---
type: pc
race: "Dragon"
class:
 - "Blue Dragon Wyrmling"
subClass:
 - "CR 3"
cover: "Blue Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/3
  - source/mm
---
###### Blue Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Blue Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 10 | 15 | 12 | 11 | 15 |
| **Mod** | +3 | +0 | +2 | +1 | +0 | +2 |

**Speed:** 30 ft., burrow 15 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +2, Con +4, Wis +2, Cha +4
**Skills:** Perception +4, Stealth +2
**Damage Immunities:** lightning

---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage plus 3 (1d6) lightning damage.

**Lightning Breath (Recharge 5–6).** The dragon exhales lightning in a 30-foot line that is 5 feet wide. Each creature in that line must make a DC 12 Dexterity saving throw, taking 22 (4d10) lightning damage on a failed save, or half as much damage on a successful one.


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