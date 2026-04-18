---
type: pc
race: "Humanoid (sorcerer)"
class:
 - "Occult Initiate"
subClass:
 - "CR 2"
cover: "Occult Initiate.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/crcotn
---
###### Occult Initiate
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Occult Initiate.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid (sorcerer) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Humanoid (sorcerer) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 14 | 10 | 16 |
| **Mod** | +0 | +2 | +1 | +2 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus one other language
**Skills:** Arcana +6, Deception +5, History +4, Perception +2

---

### Actions

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 7 (2d6) psychic damage.

**Arcane Blast (Recharge 5–6).** The initiate creates an explosion of magical force in a 20-foot-radius sphere centered on a point it can see within 120 feet of itself. Each creature in that area must make a DC 13 Dexterity saving throw. On a failed saving throw, the creature takes 10 (3d6) force damage and is pushed 10 feet away from the center of the area. On a successful save, it takes half as much damage and isn't pushed.


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