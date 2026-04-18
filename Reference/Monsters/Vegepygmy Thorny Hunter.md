---
type: pc
race: "Plant"
class:
 - "Vegepygmy Thorny Hunter"
subClass:
 - "CR 2"
cover: "Vegepygmy Thorny Hunter.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/2
  - source/qftis
---
###### Vegepygmy Thorny Hunter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Vegepygmy Thorny Hunter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 13 | 2 | 10 | 6 |
| **Mod** | +2 | +2 | +1 | -4 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4, Stealth +4, Survival +4
**Damage Resistances:** lightning; piercing

---

### Traits

**Pack Tactics.** The vegepygmy has advantage on attack rolls against a creature if at least one of the vegepygmy's allies is within 5 feet of the creature and the ally doesn't have the incapacitated condition.

**Plant Camouflage.** The vegepygmy has advantage on Dexterity (Stealth) checks it makes in any terrain with ample obscuring vegetation.

**Regeneration.** The vegepygmy regains 5 hit points at the start of its turn. If it takes cold, fire, or necrotic damage, this trait doesn't function at the start of the vegepygmy's next turn. The vegepygmy dies only if it starts its turn with 0 hit points and doesn't regenerate.

**Thorny Body.** At the start of its turn, the vegepygmy deals 2 (1d4) piercing damage to any creature grappling it.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage. If the target is a creature, it must succeed on a DC 12 Strength saving throw or have the prone condition.


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