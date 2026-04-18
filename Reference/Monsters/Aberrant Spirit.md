---
type: pc
race: "Aberration"
class:
 - "Aberrant Spirit"
subClass:
 - "CR —"
cover: "Aberrant Spirit.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/—
  - source/tce
---
###### Aberrant Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Aberrant Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 40 + 10 for each spell level above 4th |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 15 | 16 | 10 | 6 |
| **Mod** | +3 | +0 | +2 | +3 | +0 | -2 |

**Speed:** 30 ft., fly 30 ft. ((beholderkin only; hover)) (hover) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Deep Speech, understands the languages you speak
**Damage Immunities:** psychic

---

### Traits

**Regeneration (Slaad Only).** The aberration regains 5 hit points at the start of its turn if it has at least 1 hit point.

**Whispering Aura (Star Spawn Only).** At the start of each of the aberration's turns, each creature within 5 feet of the aberration must succeed on a Wisdom saving throw against your spell save DC or take 2d6 psychic damage, provided that the aberration isn't incapacitated.


---

### Actions

**Multiattack.** The aberration makes a number of attacks equal to half this spell's level (rounded down).

**Eye Ray (Beholderkin Only).** Ranged Spell Attack:  to hit, range 150 ft., one creature. *Hit:* 1d8 + 3 + summonSpellLevel psychic damage.

**Claws (Slaad Only).** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d10 + 3 + summonSpellLevel slashing damage. If the target is a creature, it can't regain hit points until the start of the aberration's next turn.

**Psychic Slam (Star Spawn Only).** Melee Spell Attack:  to hit, reach 5 ft., one creature. *Hit:* 1d8 + 3 + summonSpellLevel psychic damage.


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