---
type: pc
race: "Monstrosity"
class:
 - "The Lonely"
subClass:
 - "CR 9"
cover: "The Lonely.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/9
  - source/mtf
---
###### The Lonely
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[The Lonely.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 17 | 6 | 11 | 6 |
| **Mod** | +3 | +1 | +3 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common
**Damage Resistances:** bludgeoning, piercing, slashing while in dim light or darkness

---

### Traits

**Psychic Leech.** At the start of each of the Lonely's turns, each creature within 5 feet of it must succeed on a DC 15 Wisdom saving throw or take 10 (3d6) psychic damage.

**Thrives on Company.** The Lonely has advantage on attack rolls while it is within 30 feet of at least two other creatures. It otherwise has disadvantage on attack rolls.


---

### Actions

**Multiattack.** The Lonely makes one harpoon arm attack and uses Sorrowful Embrace.

**Harpoon Arm.** Melee Weapon Attack: +7 to hit, reach 60 ft., one target. *Hit:* 21 (4d8 + 3) piercing damage, and the target is grappled (escape DC 15) if it is a Large or smaller creature.
The Lonely has two harpoon arms and can grapple up to two creatures at once.

**Sorrowful Embrace.** Each creature grappled by the Lonely must make a DC 15 Wisdom saving throw. A creature takes 18 (4d8) psychic damage on a failed save, or half as much damage on a successful one. In either case, the Lonely pulls each creature grappled by it up to 30 feet straight toward it.


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