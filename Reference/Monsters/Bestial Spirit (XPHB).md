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
  - source/xphb
---
###### Bestial Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Bestial Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 20 (Air only) or 30 (Land and Water only) + 5 for each spell level above 2 |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 16 | 4 | 14 | 5 |
| **Mod** | +4 | +0 | +3 | -3 | +2 | -3 |

**Speed:** 30 ft., climb 30 ft. ((Land only)), fly 60 ft. ((Air only)), swim 30 ft. ((Water only)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** understands the languages you know

---

### Traits

**Flyby (Air Only).** The spirit doesn't provoke Opportunity Attacks when it flies out of an enemy's reach.

**Pack Tactics (Land and Water Only).** The spirit has Advantage on an attack roll against a creature if at least one of the spirit's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.

**Water Breathing (Water Only).** The spirit can breathe only underwater.


---

### Actions

**Multiattack.** The spirit makes a number of Rend attacks equal to half this spell's level (round down).

**Rend.** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d8 + 4 + summonSpellLevel Piercing damage.


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