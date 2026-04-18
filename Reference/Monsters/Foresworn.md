---
type: pc
race: "Undead"
class:
 - "Foresworn"
subClass:
 - "CR 6"
cover: "Foresworn.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/mcv2dc
---
###### Foresworn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV2DC
___

> [!infobox|no-t right]
> ![[Foresworn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 82 (11d8 + 33) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | MCV2DC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 17 | 12 | 18 | 10 |
| **Mod** | +5 | +2 | +3 | +1 | +4 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** the languages it knew in life
**Saving Throws:** Str +8, Wis +7
**Damage Resistances:** necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Duty-Bound.** The foresworn is bound to enacting a singular duty it pledged itself to in life. While this duty is incomplete, whenever the foresworn is destroyed, it re-forms at its previous location after 3 (1d6) days, with all its hit points restored.

**Incorporeal Movement.** The foresworn can move through other creatures and objects as if they were difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside an object.

**Unusual Nature.** The foresworn doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The foresworn makes three Spectral Polearm attacks.

**Spectral Polearm.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) force damage.


---

### Bonus Actions

**Phantasmic Battalion (Recharge 5–6).** The foresworn summons a battalion of ghostly soldiers to its aid. The ghostly soldiers fill a 10-foot-cube centered on the foresworn, move with the foresworn when the foresworn moves, and last until the start of the foresworn's next turn. While the ghostly soldiers are present, the area they occupy is considered difficult terrain for all creatures except the foresworn, and the foresworn's reach for melee weapon attacks increases by 10 feet.


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