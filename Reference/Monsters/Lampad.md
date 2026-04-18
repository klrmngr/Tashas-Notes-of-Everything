---
type: pc
race: "Fey"
class:
 - "Lampad"
subClass:
 - "CR 3"
cover: "Lampad.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/3
  - source/mot
---
###### Lampad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Lampad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fey |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 52 (8d8 + 16) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 13 | 14 | 11 | 12 | 18 |
| **Mod** | +1 | +1 | +2 | +0 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Sylvan
**Skills:** Deception +6, Intimidation +6
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Corpse Stride.** Once on its turn, the lampad can use 10 feet of its movement to step magically into one creature's corpse within its reach and emerge from a second creature's corpse within 60 feet of the first corpse, appearing in an unoccupied space within 5 feet of the second corpse. Both corpses must be Medium or bigger.

**Magic Resistance.** The lampad has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The lampad attacks twice with its necrotic touch or chill touch.

**Necrotic Touch.** Melee Spell Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) necrotic damage.

**Chill Touch (Cantrip).** Ranged Spell Attack: +6 to hit, range 120 ft., one creature. *Hit:* 9 (2d8) necrotic damage, and the target can't regain hit points until the start of the lampad's next turn. If the target is undead, it has disadvantage on attack rolls against the lampad until the end of the lampad's next turn.


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