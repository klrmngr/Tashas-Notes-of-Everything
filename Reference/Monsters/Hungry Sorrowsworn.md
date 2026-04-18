---
type: pc
race: "Monstrosity"
class:
 - "Hungry Sorrowsworn"
subClass:
 - "CR 11"
cover: "Hungry Sorrowsworn.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/11
  - source/mpmm
---
###### Hungry Sorrowsworn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Hungry Sorrowsworn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 225 (30d8 + 90) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

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

**Life Hunger.** If a creature within 60 feet of the sorrowsworn regains hit points, the sorrowsworn gains two benefits until the end of its next turn: it has advantage on attack rolls, and its Bite deals an extra 22 (4d10) necrotic damage on a hit.


---

### Actions

**Multiattack.** The sorrowsworn makes one Bite attack and one Claw attack.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) piercing damage plus 13 (3d8) necrotic damage.

**Claw.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 18 (4d6 + 4) slashing damage. If the target is Medium or smaller, it is grappled (escape DC 16), and it is restrained until the grapple ends. While grappling a creature, the sorrowsworn can't make a Claw attack.


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