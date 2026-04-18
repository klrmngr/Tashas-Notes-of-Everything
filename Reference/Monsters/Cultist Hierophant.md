---
type: pc
race: "Humanoid"
class:
 - "Cultist Hierophant"
subClass:
 - "CR 10"
cover: "Cultist Hierophant.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/10
  - source/xmm
---
###### Cultist Hierophant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Cultist Hierophant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 144 (17d8 + 68) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 18 | 13 | 16 | 20 |
| **Mod** | +2 | +4 | +4 | +1 | +3 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 17
**Languages:** Celestial, Common
**Saving Throws:** Wis +7, Cha +9
**Skills:** Perception +7, Persuasion +9, Religion +5

---

### Actions

**Multiattack.** The cultist makes three attacks, using Pact Blade or Radiant Ray in any combination.

**Pact Blade.** m +9, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 18 (4d8) Radiant damage.

**Radiant Ray.** r +9, range 120 ft. *Hit:* 31 (4d12 + 5) Radiant damage.


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