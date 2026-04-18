---
type: pc
race: "Undead"
class:
 - "Undead Spirit"
subClass:
 - "CR —"
cover: "Undead Spirit.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/—
  - source/tce
---
###### Undead Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Undead Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3rd |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 15 | 4 | 10 | 9 |
| **Mod** | +1 | +3 | +2 | -3 | +0 | -1 |

**Speed:** 30 ft., fly 40 ft. ((ghostly only; hover)) (hover) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** understands the languages you speak
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Incorporeal Passage (Ghostly Only).** The spirit can move through other creatures and objects as if they were 3. If it ends its turn inside an object, it is shunted to the nearest unoccupied space and takes 1d10 force damage for every 5 feet traveled.

**Festering Aura (Putrid Only).** Any creature, other than you, that starts its turn within 5 feet of the spirit must succeed on a Constitution saving throw against your spell save DC or be poisoned until the start of its next turn.


---

### Actions

**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (rounded down).

**Deathly Touch (Ghostly Only).** Melee Weapon Attack:  to hit, reach 5 ft., one creature. *Hit:* 1d8 + 3 + summonSpellLevel necrotic damage, and the creature must succeed on a Wisdom saving throw against your spell save DC or be frightened of the undead until the end of the target's next turn.

**Grave Bolt (Skeletal Only).** Ranged Spell Attack:  to hit, range 150 ft., one target. *Hit:* 2d4 + 3 + summonSpellLevel necrotic damage.

**Rotting Claw (Putrid Only).** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d6 + 3 + summonSpellLevel slashing damage. If the target is poisoned, it must succeed on a Constitution saving throw against your spell save DC or be paralyzed until the end of its next turn.


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