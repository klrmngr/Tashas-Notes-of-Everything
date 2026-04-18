---
type: pc
race: "Construct"
class:
 - "Living Unseen Servant"
subClass:
 - "CR 0"
cover: "Living Unseen Servant.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/0
  - source/wdmm
---
###### Living Unseen Servant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WDMM
___

> [!infobox|no-t right]
> ![[Living Unseen Servant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 4 (1d8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | WDMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 10 | 11 | 1 | 10 | 1 |
| **Mod** | -4 | +0 | +0 | -5 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft. (blind beyond this radius), passive Perception 12
**Languages:** understands one language (usually Common) but can't speak
**Skills:** Perception +2, Stealth +4
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; paralyzed; petrified; poisoned; unconscious

---

### Traits

**Invisibility.** The unseen servant is invisible.


---

### Actions

**Slam.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 1 bludgeoning damage.


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