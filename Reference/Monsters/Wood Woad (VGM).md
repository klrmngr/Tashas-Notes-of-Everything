---
type: pc
race: "Plant"
class:
 - "Wood Woad"
subClass:
 - "CR 5"
cover: "Wood Woad.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/5
  - source/vgm
---
###### Wood Woad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Wood Woad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 18 (natural armor, shield) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 16 | 10 | 13 | 8 |
| **Mod** | +4 | +1 | +3 | +0 | +1 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Sylvan
**Skills:** Athletics +7, Perception +4, Stealth +4
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing
**Condition Immunities:** charmed; frightened

---

### Traits

**Magic Club.** In the wood woad's hand, its club is magical and deals 7 (3d4) extra damage (included in its attacks).

**Plant Camouflage.** The wood woad has advantage on Dexterity (Stealth) checks it makes in any terrain with ample obscuring plant life.

**Regeneration.** The wood woad regains 10 hit points at the start of its turn if it is in contact with the ground. If the wood woad takes fire damage, this trait doesn't function at the start of the wood woad's next turn. The wood woad dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Tree Stride.** Once on each of its turns, the wood woad can use 10 feet of its movement to step magically into one living tree within 5 feet of it and emerge from a second living tree within 60 feet of it that it can see, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be Large or bigger.


---

### Actions

**Multiattack.** The wood woad makes two attacks with its club.

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