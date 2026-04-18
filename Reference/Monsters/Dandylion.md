---
type: pc
race: "Fey"
class:
 - "Dandylion"
subClass:
 - "CR 6"
cover: "Dandylion.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/6
  - source/mismv1
---
###### Dandylion
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MisMV1
___

> [!infobox|no-t right]
> ![[Dandylion.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | MisMV1 |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 19 | 14 | 16 | 17 | 18 |
| **Mod** | +6 | +4 | +2 | +3 | +3 | +4 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** Common, Sylvan
**Saving Throws:** Str +9, Cha +7
**Skills:** Nature +9, Perception +6, Survival +6

---

### Traits

**Magic Resistance.** The dandylion has advantage on saving throws against spells and other magical effects.

**Pack Tactics.** The dandylion has advantage on an attack roll against a creature if at least one of the dandylion's allies is within 5 feet of the creature and the ally doesn't have the incapacitated condition.


---

### Actions

**Multiattack.** The dandylion makes one Bite attack and one Claws attack.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) piercing damage.

**Claws.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 20 (4d6 + 6) slashing damage. If the dandylion moved at least 20 feet straight toward the target immediately before the hit, the target must succeed on a DC 17 Strength saving throw or have the prone condition. If the target has the prone condition, the dandylion can make one Bite attack against it as a bonus action.

**Rejuvenating Seedpods (2/Day).** The dandylion releases a burst of seedpods from its tail, filling a 10-foot-radius sphere centered on itself. Each creature of the dandylion's choice in the sphere can immediately end one of the following conditions on itself (creature's choice): blinded, deafened, paralyzed, or poisoned. In addition, all soil in the sphere's area is enriched, restoring withered vegetation in the area to full health and causing all crops in the area to produce twice the normal harvest for the next year.


---

### Reactions

**Roar of Pride.** When a creature within 60 feet of the dandylion hits it with an attack roll, the dandylion can unleash a furious roar. The creature that triggered this reaction must succeed on a DC 15 Wisdom saving throw or have the frightened condition until the end of the dandylion's next turn.


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