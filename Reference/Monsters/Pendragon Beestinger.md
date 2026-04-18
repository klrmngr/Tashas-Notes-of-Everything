---
type: pc
race: "Humanoid (human)"
class:
 - "Pendragon Beestinger"
subClass:
 - "CR 2"
cover: "Pendragon Beestinger.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/ai
---
###### Pendragon Beestinger
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Pendragon Beestinger.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 17 | 10 | 11 |
| **Mod** | +0 | +2 | +1 | +3 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Draconic, Elvish, Halfling
**Skills:** Arcana +5, Investigation +5, Performance +2

---

### Traits

**Echo Spell (1/Day).** Pendragon can cast the spell he cast on his last turn, whose casting time becomes 1 bonus action. This bonus casting uses a spell slot as normal.


---

### Actions

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.


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