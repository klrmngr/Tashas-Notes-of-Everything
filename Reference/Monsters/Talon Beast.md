---
type: pc
race: "Monstrosity"
class:
 - "Talon Beast"
subClass:
 - "CR 7"
cover: "Talon Beast.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/7
  - source/bmt
---
###### Talon Beast
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Book of Many Things
___

> [!infobox|no-t right]
> ![[Talon Beast.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 114 (12d10 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | The Book of Many Things |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 14 | 19 | 5 | 12 | 5 |
| **Mod** | +6 | +2 | +4 | -3 | +1 | -3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4
**Condition Immunities:** frightened

---

### Traits

**Magic Resistance.** The talon beast has advantage on saving throws against spells and other magical effects.

**Sense Magic.** The talon beast can detect and pinpoint the location of magic within 120 feet of itself.


---

### Actions

**Multiattack.** The talon beast makes two Talon attacks or a Talon attack and a Beak attack.

**Beak.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 17 (2d10 + 6) piercing damage, and if the target has any spell effects on itself or any magic items in its possession, the target must make a DC 15 Charisma saving throw. On a failed save, a random spell effect on the target ends. If the target has no spell effects on it, one random magic item in its possession has its magical properties suppressed for 1 minute. If the item is a potion or scroll, it becomes nonmagical instead.

**Talon.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 15 (2d8 + 6) slashing damage, and the target has the grappled condition (escape DC 17). Until the grapple ends, the target has the restrained condition, and the talon beast can't use Talon on another target.


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