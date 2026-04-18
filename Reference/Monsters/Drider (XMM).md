---
type: pc
race: "Monstrosity"
class:
 - "Drider"
subClass:
 - "CR 6"
cover: "Drider.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/6
  - source/xmm
---
###### Drider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Drider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 19 |
> | :FasHeart: HP | 123 (13d10 + 52) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 19 | 18 | 13 | 16 | 12 |
| **Mod** | +3 | +4 | +4 | +1 | +3 | +1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 16
**Languages:** Elvish, Undercommon
**Skills:** Perception +6, Stealth +10

---

### Traits

**Spider Climb.** The drider can climb difficult surfaces, including along ceilings, without needing to make an ability check.

**Sunlight Sensitivity.** While in sunlight, the drider has Disadvantage on ability checks and attack rolls.

**Web Walker.** The drider ignores movement restrictions caused by webs, and the drider knows the location of any other creature in contact with the same web.


---

### Actions

**Multiattack.** The drider makes three attacks, using Foreleg or Poison Burst in any combination.

**Foreleg.** m +7, reach 10 ft. *Hit:* 13 (2d8 + 4) Piercing damage.

**Poison Burst.** r +6, range 120 ft. *Hit:* 13 (3d6 + 3) Poison damage.


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