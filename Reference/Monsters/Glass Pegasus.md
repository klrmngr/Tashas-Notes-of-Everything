---
type: pc
race: "Construct"
class:
 - "Glass Pegasus"
subClass:
 - "CR 2"
cover: "Glass Pegasus.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/2
  - source/wbtw
---
###### Glass Pegasus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: The Wild Beyond the Witchlight
___

> [!infobox|no-t right]
> ![[Glass Pegasus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 15 while animated and 13 otherwise |
> | :FasHeart: HP | 59 (7d10 + 21) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | The Wild Beyond the Witchlight |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 15 | 16 | 10 | 15 | 13 |
| **Mod** | +4 | +2 | +3 | +0 | +2 | +1 |

**Speed:** 60 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Celestial, Common, Elvish and Sylvan but can't speak
**Saving Throws:** Dex +4, Wis +4, Cha +3
**Skills:** Perception +6
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified

---

### Actions

**Hooves.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.


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