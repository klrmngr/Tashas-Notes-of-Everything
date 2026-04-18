---
type: pc
race: "Plant"
class:
 - "Treant Sapling"
subClass:
 - "CR 2"
cover: "Treant Sapling.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/2
  - source/wbtw
---
###### Treant Sapling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Treant Sapling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 45 (6d10 + 12) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 8 | 15 | 12 | 12 | 10 |
| **Mod** | +3 | -1 | +2 | +1 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Common, Druidic, Elvish, Sylvan
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing

---

### Traits

**False Appearance.** If the treant is motionless at the start of combat, it has advantage on its initiative roll. Moreover, if a creature hasn't observed the treant move or act, that creature must succeed on a DC 18 Intelligence (Investigation) check to discern that the treant is animate.


---

### Actions

**Multiattack.** The treant makes two Slam attacks.

**Slam.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. *Hit:* 14 (2d10 + 3) bludgeoning damage.

**Animate Trees (1/Day).** The treant magically animates one or two trees it can see within 60 feet of it. These trees have the same statistics as an awakened tree (see the Monster Manual), except they can't speak. An animated tree acts as an ally of the treant. The tree remains animate for 1 day or until it dies, until the treant dies or is more than 120 feet from the tree, or until the treant takes a bonus action to turn it back into an inanimate tree. The tree then takes root if possible.


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