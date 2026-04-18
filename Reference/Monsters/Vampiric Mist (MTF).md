---
type: pc
race: "Undead"
class:
 - "Vampiric Mist"
subClass:
 - "CR 3"
cover: "Vampiric Mist.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/3
  - source/mtf
---
###### Vampiric Mist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Vampiric Mist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 30 (4d8 + 12) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 16 | 16 | 6 | 12 | 7 |
| **Mod** | -2 | +3 | +3 | -2 | +1 | -2 |

**Speed:** 0 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** —
**Saving Throws:** Wis +3
**Damage Resistances:** acid; cold; lightning; necrotic; thunder; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; grappled; paralyzed; petrified; poisoned; prone; restrained

---

### Traits

**Life Sense.** The mist can sense the location of any creature within 60 feet of it, unless that creature's type is construct or undead.

**Forbiddance.** The mist can't enter a residence without an invitation from one of the occupants.

**Misty Form.** The mist can occupy another creature's space and vice versa. In addition, if air can pass through a space, the mist can pass through it without squeezing. Each foot of movement in water costs it 2 extra feet, rather than 1 extra foot. The mist can't manipulate objects in any way that requires fingers or manual dexterity.

**Sunlight Hypersensitivity.** The mist takes 10 radiant damage whenever it starts its turn in sunlight. While in sunlight, the mist has disadvantage on attack rolls and ability checks.


---

### Actions

**Life Drain.** The mist touches one creature in its space. The target must succeed on a DC 13 Constitution saving throw (undead and constructs automatically succeed), or it takes 10 (2d6 + 3) necrotic damage, the mist regains 10 hit points, and the target's hit point maximum is reduced by an amount equal to the necrotic damage taken. This reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.


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