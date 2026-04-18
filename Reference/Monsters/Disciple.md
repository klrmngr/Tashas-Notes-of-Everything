---
type: pc
race: "Humanoid"
class:
 - "Disciple"
subClass:
 - "CR —"
cover: "Disciple.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/—
  - source/hol
---
###### Disciple
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: HoL
___

> [!infobox|no-t right]
> ![[Disciple.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 11 (shield) |
> | :FasHeart: HP | 9 (2d8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | HoL |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 9 | 10 | 11 | 13 | 9 |
| **Mod** | +1 | -1 | +0 | +0 | +1 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** any one language (usually Common)
**Saving Throws:** Wis +3
**Skills:** Perception +3, Religion +2

---

### Actions

**Mace.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6 + 1) bludgeoning damage.

**Sacred Flame (Cantrip).** You target one creature you can see within 60 feet of you. The target must succeed on a DC 11 Dexterity saving throw or take 4 (1d8) radiant damage. The target gains no benefit from cover for this saving throw.


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