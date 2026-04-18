---
type: pc
race: "Aberration"
class:
 - "Phaerimm Agent"
subClass:
 - "CR 8"
cover: "Phaerimm Agent.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/8
  - source/fraif
---
###### Phaerimm Agent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Phaerimm Agent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 123 (19d10 + 19) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 12 | 17 | 16 | 18 |
| **Mod** | +1 | +4 | +1 | +3 | +3 | +4 |

**Speed:** 10 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 16
**Languages:** telepathy 120 ft. understands Common and Deep Speech but can't speak
**Saving Throws:** Con +4, Int +6, Wis +6, Cha +7
**Skills:** Arcana +9, Insight +6, Perception +6
**Condition Immunities:** charmed

---

### Traits

**Magic Resistance.** The phaerimm has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The phaerimm makes three attacks, using Dread Stinger or Mindwarp Ray in any combination.

**Dread Stinger.** m +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing damage plus 13 (2d12) Poison damage.

**Mindwarp Ray.** r +7, range 120 ft. *Hit:* 13 (2d8 + 4) Psychic damage, and the target has the Charmed condition until the start of the phaerimm's next turn.


---

### Bonus Actions

**Teleport.** The phaerimm teleports up to 30 feet to an unoccupied space it can see.


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