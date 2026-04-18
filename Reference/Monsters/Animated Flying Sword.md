---
type: pc
race: "Construct"
class:
 - "Animated Flying Sword"
subClass:
 - "CR 1/4"
cover: "Animated Flying Sword.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-4
  - source/xmm
---
###### Animated Flying Sword
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Animated Flying Sword.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 14 (4d6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 11 | 1 | 5 | 1 |
| **Mod** | +1 | +2 | +0 | -5 | -3 | -5 |

**Speed:** 5 ft., fly 50 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Blindsight 60 ft., passive Perception 7
**Languages:** —
**Saving Throws:** Dex +4
**Damage Immunities:** poison; psychic
**Condition Immunities:** charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Actions

**Slash.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Slashing damage.


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