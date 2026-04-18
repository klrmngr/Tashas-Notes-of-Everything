---
type: pc
race: "Elemental"
class:
 - "Aarakocra Skirmisher"
subClass:
 - "CR 1/4"
cover: "Aarakocra Skirmisher.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/1-4
  - source/xmm
---
###### Aarakocra Skirmisher
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Aarakocra Skirmisher.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 11 | 12 | 11 |
| **Mod** | +0 | +2 | +1 | +0 | +1 | +0 |

**Speed:** 20 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Aarakocra, Primordial (Auran)
**Skills:** Perception +5

---

### Actions

**Talons.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Slashing damage, or 9 (3d4 + 2) Slashing damage if the aarakocra moved 30+ feet straight toward the target immediately before the hit.

**Wind Javelin.** m,r +4, reach 5 ft. or range 30/120 ft. *Hit:* 5 (1d6 + 2) Piercing damage plus 2 (1d4) Thunder damage. The javelin magically returns to the aarakocra's hand immediately after a ranged attack.


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