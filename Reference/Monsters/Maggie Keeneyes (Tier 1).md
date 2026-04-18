---
type: pc
race: "Giant (ogre)"
class:
 - "Maggie Keeneyes (Tier 1)"
subClass:
 - "CR 3"
cover: "Maggie Keeneyes (Tier 1).png"
campaign:
locations:
tags:
  - race/ogre
  - affinity/hostile
  - type/giant
  - size/large
  - cr/3
  - source/crcotn
---
###### Maggie Keeneyes (Tier 1)
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Maggie Keeneyes (Tier 1).png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Giant (ogre) |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 85 (10d10 + 30) |
> | :FasUserGroup: Race | Giant (ogre) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 14 | 16 | 14 | 14 | 8 |
| **Mod** | +4 | +2 | +3 | +2 | +2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** Common, Giant
**Saving Throws:** Str +6, Con +5
**Skills:** Athletics +6, Insight +4, Perception +4, Persuasion +3

---

### Traits

**Tactical Readiness.** Maggie and allies within 30 feet of her have advantage on initiative rolls, as long as Maggie isn't incapacitated.


---

### Actions

**Giant Maul.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage, and if the target is a creature, Maggie can force it to make a DC 14 Strength saving throw; on a failed save, the target is pushed 5 feet away from Maggie and knocked prone.

**Hammer Toss.** Ranged Weapon Attack: +6 to hit, range 20/60 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage, and if the target is a creature, Maggie can force it to make a DC 14 Strength saving throw; on a failed save, the target is pushed 5 feet away from Maggie and knocked prone.


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