---
type: pc
race: "Construct"
class:
 - "Animated Rug of Smothering"
subClass:
 - "CR 2"
cover: "Animated Rug of Smothering.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/2
  - source/xmm
---
###### Animated Rug of Smothering
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Animated Rug of Smothering.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (5d10) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 10 | 1 | 3 | 1 |
| **Mod** | +3 | +2 | +0 | -5 | -4 | -5 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 6
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Actions

**Smother.** m +5, reach 5 ft. *Hit:* 10 (2d6 + 3) Bludgeoning damage. If the target is a Medium or smaller creature, the rug can give it the Grappled condition (escape DC 13) instead of dealing damage. Until the grapple ends, the target has the Blinded and Restrained conditions, is suffocating, and takes 10 (2d6 + 3) Bludgeoning damage at the start of each of its turns. The rug can smother only one creature at a time.
While grappling the target, the rug can't take this action, the rug halves the damage it takes (round down), and the target takes the same amount of damage.


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