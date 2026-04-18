---
type: pc
race: "Aberration (shapechanger)"
class:
 - "Death Slaad"
subClass:
 - "CR 10"
cover: "Death Slaad.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/10
  - source/mm
---
###### Death Slaad
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Death Slaad.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Aberration (shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 170 (20d8 + 80) |
> | :FasUserGroup: Race | Aberration (shapechanger) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 19 | 15 | 10 | 16 |
| **Mod** | +5 | +2 | +4 | +2 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 60 ft., passive Perception 18
**Languages:** Slaad, telepathy 60 ft.
**Skills:** Arcana +6, Perception +8
**Damage Resistances:** acid; cold; fire; lightning; thunder

---

### Traits

**Shapechanger.** The slaad can use its action to polymorph into a Small or Medium humanoid, or back into its true form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies.

**Magic Resistance.** The slaad has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The slaad's weapon attacks are magical.

**Regeneration.** The slaad regains 10 hit points at the start of its turn if it has at least 1 hit point.


---

### Actions

**Multiattack.** The slaad makes three attacks: one with its bite and two with its claws or greatsword.

**Bite (Slaad Form Only).** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8 + 5) piercing damage plus 7 (2d6) necrotic damage.

**Claws (Slaad Form Only).** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) slashing damage plus 7 (2d6) necrotic damage.

**Greatsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 7 (2d6) necrotic damage.


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