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
  - source/xphb
---
###### Undead Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Undead Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 30 (Ghostly and Putrid only) or 20 (Skeletal only) + 10 for each spell level above 3 |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 15 | 4 | 10 | 9 |
| **Mod** | +1 | +3 | +2 | -3 | +0 | -1 |

**Speed:** 30 ft., fly 40 ft. ((hover; Ghostly only)) (hover) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** understands the languages you know
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Festering Aura (Putrid Only).** con DC equals your spell save DC, any creature (other than you) that starts its turn within a 5-foot Emanation originating from the spirit.  The creature has the Poisoned condition until the start of its next turn.

**Incorporeal Passage (Ghostly Only).** The spirit can move through other creatures and objects as if they were Difficult Terrain. If it ends its turn inside an object, it is shunted to the nearest unoccupied space and takes 1d10 Force damage for every 5 feet traveled.


---

### Actions

**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (round down).

**Deathly Touch (Ghostly Only).** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d8 + 3 + summonSpellLevel Necrotic damage, and the target has the Frightened condition until the end of its next turn.

**Grave Bolt (Skeletal Only).** r Bonus equals your spell attack modifier, range 150 ft. *Hit:* 2d4 + 3 + summonSpellLevel Necrotic damage.

**Rotting Claw (Putrid Only).** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d6 + 3 + summonSpellLevel Slashing damage. If the target has the Poisoned condition, it has the Paralyzed condition until the end of its next turn.


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