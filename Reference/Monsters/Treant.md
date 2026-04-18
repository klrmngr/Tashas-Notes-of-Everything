---
type: pc
race: "Plant"
class:
 - "Treant"
subClass:
 - "CR 9"
cover: "Treant.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/huge
  - cr/9
  - source/mm
---
###### Treant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Treant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Plant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 8 | 21 | 12 | 16 | 12 |
| **Mod** | +6 | -1 | +5 | +1 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Druidic, Elvish, Sylvan
**Damage Vulnerabilities:** fire
**Damage Resistances:** bludgeoning; piercing

---

### Traits

**False Appearance.** While the treant remains motionless, it is indistinguishable from a normal tree.

**Siege Monster.** The treant deals double damage to objects and structures.


---

### Actions

**Multiattack.** The treant makes two slam attacks.

**Slam.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +10 to hit, range 60/180 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage.

**Animate Trees (1/Day).** The treant magically animates one or two trees it can see within 60 feet of it. These trees have the same statistics as a treant, except they have Intelligence and Charisma scores of 1, they can't speak, and they have only the Slam action option. An animated tree acts as an ally of the treant. The tree remains animate for 1 day or until it dies; until the treant dies or is more than 120 feet from the tree; or until the treant takes a bonus action to turn it back into an inanimate tree. The tree then takes root if possible.


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