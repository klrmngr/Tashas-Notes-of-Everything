---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Ghelryn Foehammer"
subClass:
 - "CR —"
cover: "Ghelryn Foehammer.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/skt
---
###### Ghelryn Foehammer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Ghelryn Foehammer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 14 (breastplate, shield) |
> | :FasHeart: HP | 30 (4d8 + 12) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 7 | 17 | 10 | 11 | 11 |
| **Mod** | +4 | -2 | +3 | +0 | +0 | +0 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common, Dwarvish
**Skills:** Athletics +6, Intimidation +2, Perception +2
**Damage Resistances:** poison

---

### Traits

**Dwarven Resilience.** Ghelryn has advantage on saving throws against poison.

**Giant Slayer.** Any weapon attack that Ghelryn makes against a giant deals an extra 7 (2d6) damage on a hit.

**Roleplaying Information.** The blacksmith Ghelryn has a good heart, but he hates orcs and giants—hates them with a fiery passion. He considers it the solemn duty of all dwarves to cave in their skulls!
Ideal: "It is incumbent upon every dwarf to forge a legacy."
Bond: "I stand for Clan Foehammer and all dwarvenkind."
Flaw: "I never run from a fight, especially if it involves killing orcs or giants."


---

### Actions

**Multiattack.** Ghelryn makes two battleaxe attacks.

**Battleaxe.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands.


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