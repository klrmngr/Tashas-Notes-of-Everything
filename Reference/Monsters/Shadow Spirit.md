---
type: pc
race: "Monstrosity"
class:
 - "Shadow Spirit"
subClass:
 - "CR —"
cover: "Shadow Spirit.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/—
  - source/tce
---
###### Shadow Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Shadow Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 35 + 15 for each spell level above 3rd |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 15 | 4 | 10 | 16 |
| **Mod** | +1 | +3 | +2 | -3 | +0 | +3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** understands the languages you speak
**Damage Resistances:** necrotic
**Condition Immunities:** frightened

---

### Traits

**Terror Frenzy (Fury Only).** The spirit has advantage on attack rolls against frightened creatures.

**Weight of Sorrow (Despair Only).** Any creature, other than you, that starts its turn within 5 feet of the spirit has its speed reduced by 20 feet until the start of that creature's next turn.


---

### Actions

**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (rounded down).

**Chilling Rend.** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d12 + 3 + summonSpellLevel cold damage.

**Dreadful Scream (1/Day).** The spirit screams. Each creature within 30 feet of it must succeed on a Wisdom saving throw against your spell save DC or be frightened for 1 minute. The frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


---

### Bonus Actions

**Shadow Stealth (Fear Only).** While in dim light or darkness, the spirit takes the Hide action.


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