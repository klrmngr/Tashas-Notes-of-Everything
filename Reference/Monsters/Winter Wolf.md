---
type: pc
race: "Monstrosity"
class:
 - "Winter Wolf"
subClass:
 - "CR 3"
cover: "Winter Wolf.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/3
  - source/mm
---
###### Winter Wolf
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Winter Wolf.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 14 | 7 | 12 | 8 |
| **Mod** | +4 | +1 | +2 | -2 | +1 | -1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Giant, Winter Wolf
**Skills:** Perception +5, Stealth +3
**Damage Immunities:** cold

---

### Traits

**Keen Hearing and Smell.** The wolf has advantage on Wisdom (Perception) checks that rely on hearing or smell.

**Pack Tactics.** The wolf has advantage on an attack roll against a creature if at least one of the wolf's allies is within 5 feet of the creature and the ally isn't incapacitated.

**Snow Camouflage.** The wolf has advantage on Dexterity (Stealth) checks made to hide in snowy terrain.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be knocked prone.

**Cold Breath (Recharge 5–6).** The wolf exhales a blast of freezing wind in a 15-foot cone. Each creature in that area must make a DC 12 Dexterity saving throw, taking 18 (4d8) cold damage on a failed save, or half as much damage on a successful one.


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