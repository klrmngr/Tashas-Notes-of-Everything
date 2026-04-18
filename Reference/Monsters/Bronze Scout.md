---
type: pc
race: "Construct"
class:
 - "Bronze Scout"
subClass:
 - "CR 1"
cover: "Bronze Scout.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/mtf
---
###### Bronze Scout
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Bronze Scout.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 18 (4d8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 11 | 3 | 14 | 1 |
| **Mod** | +0 | +3 | +0 | -4 | +2 | -5 |

**Speed:** 30 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** understands one language of its creator but can't speak
**Skills:** Perception +6, Stealth +7
**Damage Immunities:** poison; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Earth Armor.** The bronze scout doesn't provoke opportunity attacks when it burrows.

**Magic Resistance.** The bronze scout has advantage on saving throws against spells and other magical effects.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 3 (1d6) lightning damage.

**Lightning Flare (Recharges after a Short or Long Rest).** Each creature in contact with the ground within 15 feet of the bronze scout must make a DC 13 Dexterity saving throw, taking 14 (4d6) lightning damage on a failed save, or half as much damage on a successful one.


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