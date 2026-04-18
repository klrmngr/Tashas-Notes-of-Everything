---
type: pc
race: "Plant"
class:
 - "Dirt-Under-Nails"
subClass:
 - "CR 7"
cover: "Dirt-Under-Nails.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/7
  - source/rtg
---
###### Dirt-Under-Nails
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: RtG
___

> [!infobox|no-t right]
> ![[Dirt-Under-Nails.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | RtG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 15 | 12 | 12 | 18 |
| **Mod** | +0 | +2 | +2 | +1 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** telepathy 60 ft.
**Saving Throws:** Wis +4, Cha +7
**Skills:** Arcana +4, Deception +7, Persuasion +7, Religion +4
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Dark One's Own Luck (Recharges after a Short or Long Rest).** When the warlock makes an ability check or saving throw, it can add a d10 to the roll. It can do this after the roll is made but before any of the roll's effects occur.

**Regeneration.** Dirt-Under-Nails regains 10 hit points at the start of his turn if he is in contact with the ground. If Dirt-Under-Nails takes fire damage, this trait doesn't function at the start of his next turn. Dirt-Under-Nails dies only if he starts his turn with 0 hit points and doesn't regenerate.

**Shared Senses.** Dirt-Under-Nails can see and hear what any plant within 120 ft can see and hear. In addition, Dirt-Under- Nails can communicate telepathically with any plant within this range.

**Special Equipment (+2 Rod of the Pact Keeper).** While holding this rod, Dirt-Under-Nails gains a +2 bonus to spell attack rolls and to the saving throw DCs of his warlock spells (included in modifications, below). In addition, he can regain 1 warlock spell slot as an action while holding the rod. He can't use this property again until he finishes a long rest.

**Tree Stride.** Once on each of its turns, Dirt-Under-Nails can use 10 feet of his movement to step magically into one copse of mushrooms within 5 feet of him and emerge from a second copse of mushrooms within 60 feet of it, appearing in an unoccupied space within 5 feet of the second copse. Both copses of mushrooms must be Large or bigger. Dirt-Under-Nails doesn't need to be able to see the second copse to use this ability.


---

### Actions

**Mace.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d6) bludgeoning damage plus 10 (3d6) fire damage.


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