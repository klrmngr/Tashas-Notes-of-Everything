---
type: pc
race: "Humanoid (human)"
class:
 - "Thurstwell Vanthampur"
subClass:
 - "CR 1/8"
cover: "Thurstwell Vanthampur.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-8
  - source/bgdia
---
###### Thurstwell Vanthampur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Thurstwell Vanthampur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 5 (2d8 - 4) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 8 | 6 | 15 | 17 | 12 |
| **Mod** | -2 | -1 | -2 | +2 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common, Elvish, Infernal
**Skills:** Deception +3, Insight +5, Perception +5, Religion +4

---

### Traits

**Dark Devotion.** Thurstwell has advantage on saving throws against being charmed or frightened.


---

### Actions

**Sacred Flame (Cantrip).** Flame-like radiance descends on one creature Thurstwell can see within 60 feet of him. The target must succeed on a DC 13 Dexterity saving throw or take 4 (1d8) radiant damage, gaining no benefit from cover.


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