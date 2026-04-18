---
type: pc
race: "Plant (druid)"
class:
 - "Treefolk"
subClass:
 - "CR 11"
cover: "Treefolk.png"
campaign:
locations:
tags:
  - race/druid
  - affinity/hostile
  - type/plant
  - size/large
  - cr/11
  - source/mcv4ec
---
###### Treefolk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Treefolk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Large Plant (druid) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 171 (18d10 + 72) |
> | :FasUserGroup: Race | Plant (druid) |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 12 | 18 | 10 | 20 | 11 |
| **Mod** | +6 | +1 | +4 | +0 | +5 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 19
**Languages:** Common, Druidic, Sylvan
**Saving Throws:** Con +8, Int +4, Wis +9
**Skills:** Insight +9, Nature +8, Perception +9
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing

---

### Traits

**Plant Camouflage.** The treefolk has advantage on Dexterity (Stealth) checks it makes in forest terrain.

**Tree Stride.** Once on each of its turns, the treefolk can use 10 feet of its movement to step magically into one living tree within 5 feet of itself and emerge from a second living tree within 60 feet of itself that it can see, appearing in an unoccupied space within 5 feet of the second tree. Both trees must be at least as large as the treefolk.


---

### Actions

**Multiattack.** The treefolk makes two Crushing Vine attacks, two Nightshade Bolt attacks, or one of each.

**Crushing Vine.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 25 (3d12 + 6) bludgeoning damage. If the target is a creature, it has the grappled condition (escape DC 18). While grappled, the creature also has the restrained condition. The treefolk can grapple up to six creatures this way.

**Nightshade Bolt.** Ranged Spell Attack: +9 to hit, range 60 ft., one target. *Hit:* 33 (6d10) poison damage.


---

### Bonus Actions

**Oaken Boon.** The treefolk blesses one creature other than itself that it can see within 60 feet of itself with the might and wisdom of the forest. While blessed in this way, a creature can use the treefolk's Tree Stride trait and gains 5 (2d4) temporary hit points at the start of each of its turns. This blessing lasts for 1 minute, until the treefolk has the incapacitated condition, or until the treefolk uses this bonus action again.


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