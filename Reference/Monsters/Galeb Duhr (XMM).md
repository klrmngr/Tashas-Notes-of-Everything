---
type: pc
race: "Elemental"
class:
 - "Galeb Duhr"
subClass:
 - "CR 6"
cover: "Galeb Duhr.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/6
  - source/xmm
---
###### Galeb Duhr
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Galeb Duhr.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 123 (13d8 + 65) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 20 | 11 | 12 | 11 |
| **Mod** | +5 | +2 | +5 | +0 | +1 | +0 |

**Speed:** 15 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., Tremorsense 60 ft., passive Perception 11
**Languages:** Primordial (Terran)
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Actions

**Avalanche Slam.** m +8, reach 5 ft. *Hit:* 12 (2d6 + 5) Bludgeoning damage. If the target is a Large or smaller creature and the galeb duhr moved 20+ feet straight toward it immediately before the hit, the target takes an extra 7 (2d6) Bludgeoning damage and has the Prone condition.

**Animate Boulders (1/Day).** The galeb duhr magically animates one or two boulders it can see within 60 feet of itself. Each boulder uses the Galeb Duhr stat block, except it has Intelligence and Charisma scores of 1 and lacks this action. The boulder takes its turn immediately after the galeb duhr on the same Initiative count, and it obeys the galeb duhr. A boulder remains animate for 1 minute or until it or the galeb duhr dies.


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