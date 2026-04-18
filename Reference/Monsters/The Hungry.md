---
type: pc
race: "Monstrosity"
class:
 - "The Hungry"
subClass:
 - "CR 11"
cover: "The Hungry.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/11
  - source/mtf
---
###### The Hungry
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[The Hungry.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 225 (30d8 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 6 | 11 | 6 |
| **Mod** | +4 | +0 | +3 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common
**Damage Resistances:** bludgeoning, piercing, slashing while in dim light or darkness

---

### Traits

**Life Hunger.** If a creature the Hungry can see regains hit points, the Hungry gains two benefits until the end of its next turn: it has advantage on attack rolls, and its bite deals an extra 22 (4d10) necrotic damage on a hit.


---

### Actions

**Multiattack.** The Hungry makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage plus 13 (3d8) necrotic damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 18 (4d6 + 4) slashing damage. If the target is Medium or smaller, it is grappled (escape DC 16) and is restrained until the grapple ends. While grappling a creature, the Hungry can't attack with its claws.


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