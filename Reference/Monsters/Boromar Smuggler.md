---
type: pc
race: "Humanoid (halfling)"
class:
 - "Boromar Smuggler"
subClass:
 - "CR 1/2"
cover: "Boromar Smuggler.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-2
  - source/efa
---
###### Boromar Smuggler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Boromar Smuggler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 27 (6d6 + 6) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 15 | 12 | 11 | 10 | 14 |
| **Mod** | +0 | +2 | +1 | +0 | +0 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Halfling, Thieves' cant
**Saving Throws:** Dex +4, Wis +2
**Skills:** Perception +2, Sleight Of Hand +6, Stealth +6

---

### Traits

**Hustle.** The smuggler can move through the space of any creature that is of a larger size, but it can't stop there.


---

### Actions

**Shortsword.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 2 (1d4) Poison damage.

**Pistol.** r +4, range 30/90 ft. *Hit:* 7 (1d10 + 2) Piercing damage.


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