---
type: pc
race: "Beast"
class:
 - "Bestial Spirit"
subClass:
 - "CR —"
cover: "Bestial Spirit.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/—
  - source/tce
---
###### Bestial Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Bestial Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 20 (Air only) or 30 (Land and Water only) + 5 for each spell level above 2nd |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 16 | 4 | 14 | 5 |
| **Mod** | +4 | +0 | +3 | -3 | +2 | -3 |

**Speed:** 30 ft., climb 30 ft. ((land only)), fly 60 ft. ((air only)), swim 30 ft. ((water only)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** understands the languages you speak

---

### Traits

**Water Breathing (Water Only).** The beast can breathe only underwater.

**Flyby (Air Only).** The beast doesn't provoke opportunity attacks when it flies out of an enemy's reach.

**Pack Tactics (Land and Water Only).** The beast has advantage on an attack roll against a creature if at least one of the beast's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The beast makes a number of attacks equal to half this spell's level (rounded down).

**Maul.** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d8 + 4 + summonSpellLevel piercing damage.


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