---
type: pc
race: "Monstrosity"
class:
 - "Wretched Sorrowsworn"
subClass:
 - "CR 1/4"
cover: "Wretched Sorrowsworn.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/1-4
  - source/mpmm
---
###### Wretched Sorrowsworn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Wretched Sorrowsworn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 10 (4d6 - 4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 12 | 9 | 5 | 6 | 5 |
| **Mod** | -2 | +1 | -1 | -3 | -2 | -3 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** —
**Damage Resistances:** bludgeoning, piercing, slashing while in dim light or darkness

---

### Traits

**Wretched Pack Tactics.** The sorrowsworn has advantage on an attack roll against a creature if at least one of the sorrowsworn's allies is within 5 feet of the creature and the ally isn't incapacitated. The sorrowsworn otherwise has disadvantage on attack rolls.


---

### Actions

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 6 (1d10 + 1) piercing damage, and the sorrowsworn attaches to the target. While attached, the sorrowsworn can't attack, and at the start of each of the sorrowsworn's turns, the target takes 6 (1d10 + 1) necrotic damage.
The attached sorrowsworn moves with the target whenever the target moves, requiring none of the sorrowsworn's movement. The sorrowsworn can detach itself by spending 5 feet of its movement on its turn. A creature, including the target, can use its action to detach the sorrowsworn.


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