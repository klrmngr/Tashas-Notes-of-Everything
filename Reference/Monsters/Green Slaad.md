---
type: pc
race: "Aberration (shapechanger)"
class:
 - "Green Slaad"
subClass:
 - "CR 8"
cover: "Green Slaad.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/8
  - source/mm
---
###### Green Slaad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Green Slaad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Aberration (shapechanger) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 127 (15d10 + 45) |
> | :FasUserGroup: Race | Aberration (shapechanger) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 11 | 8 | 12 |
| **Mod** | +4 | +2 | +3 | +0 | -1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 60 ft., passive Perception 12
**Languages:** Slaad, telepathy 60 ft.
**Skills:** Arcana +3, Perception +2
**Damage Resistances:** acid; cold; fire; lightning; thunder

---

### Traits

**Shapechanger.** The slaad can use its action to polymorph into a Small or Medium humanoid, or back into its true form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Magic Resistance.** The slaad has advantage on saving throws against spells and other magical effects.

**Regeneration.** The slaad regains 10 hit points at the start of its turn if it has at least 1 hit point.


---

### Actions

**Multiattack.** The slaad makes three attacks: one with its bite and two with its claws or staff. Alternatively, it uses its Hurl Flame twice.

**Bite (Slaad Form Only).** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage.

**Claw (Slaad Form Only).** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Staff.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Hurl Flame.** Ranged Spell Attack: +4 to hit, range 60 ft., one target. *Hit:* 10 (3d6) fire damage. The fire ignites flammable objects that aren't being worn or carried.


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