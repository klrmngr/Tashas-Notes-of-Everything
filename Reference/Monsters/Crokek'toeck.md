---
type: pc
race: "Fiend (demon)"
class:
 - "Crokek'toeck"
subClass:
 - "CR 14"
cover: "Crokek'toeck.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/gargantuan
  - cr/14
  - source/bgdia
---
###### Crokek'toeck
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Crokek'toeck.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 14 (11,500 XP) |
> | :RiSwordFill: Type | Gargantuan Fiend (demon) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 297 (17d20 + 119) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 10 | 24 | 6 | 10 | 13 |
| **Mod** | +9 | +0 | +7 | -2 | +0 | +1 |

**Speed:** 60 ft., swim 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands Abyssal but can't speak
**Saving Throws:** Con +12, Wis +5
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Amphibious.** Crokek'toeck can breathe air and water.

**Magic Resistance.** Crokek'toeck has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** Crokek'toeck's weapon attacks are magical.

**Secure Memory.** Crokek'toeck is immune to the waters of the River Styx as well as any effect that would steal or modify its memories or detect or read its thoughts.

**Standing Leap.** Crokek'toeck's long jump is up to 60 feet and its high jump is up to 30 feet, with or without a running start.


---

### Actions

**Bite.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 44 (10d6 + 9) piercing damage.

**Disgorge Allies (Recharge 6).** Crokek'toeck opens its mouth and disgorges 1d4 [[Barlgura|barlguras]], 3d6 [[Gnoll|gnolls]] led by 1 [[gnoll fang of Yeenoghu]], 6d6 [[Dretch|dretches]], or 1d3 [[Vrock|vrocks]]. Each creature it disgorges appears in an unoccupied space within 30 feet of Crokek'toeck's mouth, or the next closest unoccupied space.


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