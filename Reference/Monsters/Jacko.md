---
type: pc
race: "Humanoid (halfling)"
class:
 - "Jacko"
subClass:
 - "CR 1"
cover: "Jacko.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/hotb
---
###### Jacko
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HotB
___

> [!infobox|no-t right]
> ![[Jacko.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | HotB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 10 | 12 | 14 | 16 |
| **Mod** | +0 | +3 | +0 | +1 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common, Halfling
**Skills:** Perception +6, Stealth +5

---

### Traits

**Quick Disguise.** Jacko spends 1 minute to disguise himself as a different Humanoid of approximately his height and weight. While Jacko is disguised, a creature that takes the Study action to inspect Jacko's appearance can make a DC 13 Intelligence (Investigation) check, discerning his disguise on a successful check.


---

### Actions

**Multiattack.** Jacko makes two Poison Dagger attacks.

**Poison Dagger.** m,r +5, reach 5 ft. or range 20/60 ft. *Hit:* 5 (1d4 + 3) Piercing damage plus 3 (1d6) Poison damage.


---

### Bonus Actions

**Cunning Action.** Jacko takes the Dash, Disengage, or Hide action.


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