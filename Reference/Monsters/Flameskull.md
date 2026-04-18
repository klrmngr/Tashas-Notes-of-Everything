---
type: pc
race: "Undead"
class:
 - "Flameskull"
subClass:
 - "CR 4"
cover: "Flameskull.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/tiny
  - cr/4
  - source/mm
---
###### Flameskull
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Flameskull.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Tiny Undead |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 40 (9d4 + 18) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 1 | 17 | 14 | 16 | 10 | 11 |
| **Mod** | -5 | +3 | +2 | +3 | +0 | +0 |

**Speed:** 0 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Common
**Skills:** Arcana +5, Perception +2
**Damage Resistances:** lightning; necrotic; piercing
**Damage Immunities:** cold; fire; poison
**Condition Immunities:** charmed; frightened; paralyzed; poisoned; prone

---

### Traits

**Illumination.** The flameskull sheds either dim light in a 15-foot radius, or bright light in a 15-foot radius and dim light for an additional 15 feet. It can switch between the options as an action.

**Magic Resistance.** The flameskull has advantage on saving throws against spells and other magical effects.

**Rejuvenation.** If the flameskull is destroyed, it regains all its hit points in 1 hour unless holy water is sprinkled on its remains or a dispel magic or remove curse spell is cast on them.


---

### Actions

**Multiattack.** The flameskull uses Fire Ray twice.

**Fire Ray.** Ranged Spell Attack: +5 to hit, range 30 ft., one target. *Hit:* 10 (3d6) fire damage.


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