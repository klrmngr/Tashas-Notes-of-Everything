---
type: pc
race: "Construct"
class:
 - "Rotter"
subClass:
 - "CR 5"
cover: "Rotter.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/5
  - source/rtg
---
###### Rotter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: RtG
___

> [!infobox|no-t right]
> ![[Rotter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor, shield) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | RtG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 10 | 13 | 8 |
| **Mod** | +4 | +1 | +3 | +0 | +1 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** telepathy 60 ft.
**Skills:** Athletics +7, Perception +4, Stealth +4
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing
**Damage Immunities:** poison
**Condition Immunities:** charmed; frightened; poisoned

---

### Traits

**Magic Club.** In the rotter's hand, its club is magical and deals 7 (3d4) extra damage (included in its attacks).

**Plant Camouflage.** The rotter has advantage on Dexterity (Stealth) checks it makes in terrain with ample obscuring plant life.

**Regeneration.** The rotter regains 10 hit points at the start of its turn if it is in contact with the ground. If the rotter takes fire damage, this trait doesn't function at the start of the rotter's next turn. The rotter dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Shared Senses.** The rotter can see and hear what any plant within 120 ft can see and hear. In addition, the rotter can communicate telepathically with any plant within this range.

**Tree Stride.** Once on each of its turns, the rotter can use 10 feet of its movement to step magically into one copse of mushrooms within 5 feet of it and emerge from a second copse of mushrooms within 60 feet of it, appearing in an unoccupied space within 5 feet of the second copse. Both copses of mushrooms must be Large or bigger. The rotter doesn't need to be able to see the second copse to use this ability.


---

### Actions

**Multiattack.** The rotter makes two attacks with its club.

**Club.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (4d4 + 4) bludgeoning damage.


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