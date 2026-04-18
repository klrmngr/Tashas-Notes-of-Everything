---
type: pc
race: "Construct"
class:
 - "Animated Armor"
subClass:
 - "CR 1"
cover: "Animated Armor.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/xmm
---
###### Animated Armor
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Animated Armor.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 13 | 1 | 3 | 1 |
| **Mod** | +2 | +0 | +1 | -5 | -4 | -5 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 6
**Languages:** —
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Actions

**Multiattack.** The armor makes two Slam attacks.

**Slam.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Bludgeoning damage.


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