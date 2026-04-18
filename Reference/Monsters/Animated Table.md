---
type: pc
race: "Construct"
class:
 - "Animated Table"
subClass:
 - "CR 2"
cover: "Animated Table.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/2
  - source/tftyp
---
###### Animated Table
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Animated Table.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 39 (6d10 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 8 | 13 | 1 | 3 | 1 |
| **Mod** | +4 | -1 | +1 | -5 | -4 | -5 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 6
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Antimagic Susceptibility.** The table is incapacitated while in the area of an antimagic field. If targeted by dispel magic, the table must succeed on a Constitution saving throw against the caster's spell save DC or fall unconscious for 1 minute.

**False Appearance.** While the table remains motionless, it is indistinguishable from a normal table.

**Charge.** If the table moves at least 20 feet straight toward a target and then hits it with a ram attack on the same turn, the target takes an extra 9 (2d8) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.


---

### Actions

**Ram.** Melee Weapon Attack: +6, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage.


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