---
type: pc
race: "Plant"
class:
 - "Vegepygmy Scavenger"
subClass:
 - "CR 1/4"
cover: "Vegepygmy Scavenger.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/small
  - cr/1-4
  - source/qftis
---
###### Vegepygmy Scavenger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Vegepygmy Scavenger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Plant |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 14 | 13 | 6 | 11 | 7 |
| **Mod** | -2 | +2 | +1 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Vegepygmy
**Skills:** Perception +2, Sleight Of Hand +4, Stealth +4
**Damage Resistances:** lightning; piercing

---

### Traits

**Plant Camouflage.** The vegepygmy has advantage on Dexterity (Stealth) checks it makes in any terrain with ample obscuring vegetation.

**Regeneration.** The vegepygmy regains 3 hit points at the start of its turn. If it takes cold, fire, or necrotic damage, this trait doesn't function at the start of the vegepygmy's next turn. The vegepygmy dies only if it starts its turn with 0 hit points and doesn't regenerate.


---

### Actions

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Sling.** Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage.


---

### Bonus Actions

**Nimble Escape.** The vegepygmy takes the Disengage or Hide action.


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