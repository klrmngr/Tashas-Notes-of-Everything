---
type: pc
race: "Humanoid (any race)"
class:
 - "Goon"
subClass:
 - "CR 1/8"
cover: "Goon.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/nrh-ass
---
###### Goon
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: NRH-ASS
___

> [!infobox|no-t right]
> ![[Goon.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 (leather armor) |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | NRH-ASS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 12 | 10 | 10 | 11 | 10 |
| **Mod** | +0 | +1 | +0 | +0 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common

---

### Traits

**Goon Grit.** The goon has advantage on saving throws against being charmed, intimidated, or persuaded.


---

### Actions

**Scimitar.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) slashing damage.


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