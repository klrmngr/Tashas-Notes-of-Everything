---
type: pc
race: "Undead"
class:
 - "Reaper Spirit"
subClass:
 - "CR —"
cover: "Reaper Spirit.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/—
  - source/bmt
---
###### Reaper Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Reaper Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 40 + 10 for each spell level above 4th |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 16 | 16 | 16 | 16 | 16 |
| **Mod** | +3 | +3 | +3 | +3 | +3 | +3 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** understands the languages you speak
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Incorporeal Movement.** The spirit can move through other creatures and objects as if they were difficult terrain. If it ends its turn inside an object, it is shunted to the nearest unoccupied space and takes 1d10 force damage for every 5 feet shunted.


---

### Actions

**Multiattack.** The spirit makes a number of Reaping Scythe attacks equal to half the level of the spell (rounded down).

**Reaping Scythe.** Melee Weapon Attack: your spell attack modifier to hit (with advantage), reach 5 ft., the creature haunted by Haunt Creature. *Hit:* 1d8 + 3 + summonSpellLevel necrotic damage.


---

### Bonus Actions

**Haunt Creature.** The spirit targets a creature it can see within 10 feet of itself and begins haunting it. While the target is haunted, you and the spirit sense the direction and distance to the target if it is on the same plane of existence as you. Additionally, if the target starts its turn within 10 feet of the spirit, the target must succeed on a Wisdom saving throw against your spell save DC or have the frightened condition until the start of the target's next turn. The target remains haunted until it dies, the spirit disappears, or the spirit uses this action again.


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