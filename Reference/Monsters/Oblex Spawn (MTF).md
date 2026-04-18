---
type: pc
race: "Ooze"
class:
 - "Oblex Spawn"
subClass:
 - "CR 1/4"
cover: "Oblex Spawn.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/tiny
  - cr/1-4
  - source/mtf
---
###### Oblex Spawn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Oblex Spawn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Tiny Ooze |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 18 (4d4 + 8) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 15 | 14 | 11 | 10 |
| **Mod** | -1 | +3 | +2 | +2 | +0 | +0 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this distance), passive Perception 12
**Languages:** —
**Saving Throws:** Int +4, Cha +2
**Condition Immunities:** blinded; charmed; deafened; exhaustion; prone

---

### Traits

**Amorphous.** The oblex can move through a space as narrow as 1 inch wide without squeezing.

**Aversion to Fire.** If the oblex takes fire damage, it has disadvantage on attack rolls and ability checks until the end of its next turn.


---

### Actions

**Pseudopod.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) bludgeoning damage plus 2 (1d4) psychic damage.


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