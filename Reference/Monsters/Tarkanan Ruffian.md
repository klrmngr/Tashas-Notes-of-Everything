---
type: pc
race: "Humanoid"
class:
 - "Tarkanan Ruffian"
subClass:
 - "CR 1"
cover: "Tarkanan Ruffian.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1
  - source/efa
---
###### Tarkanan Ruffian
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: EFA
___

> [!infobox|no-t right]
> ![[Tarkanan Ruffian.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | EFA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 13 | 15 | 11 | 10 | 13 |
| **Mod** | +2 | +1 | +2 | +0 | +0 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common, Thieves' cant
**Saving Throws:** Dex +3, Con +4
**Skills:** Intimidation +3, Perception +2

---

### Traits

**Aberrant Surge.** When the ruffian casts Witch Bolt, roll 1d8. On an even number, the ruffian gains a number of Temporary Hit Points equal to the number rolled. On an odd number, one creature of the ruffian's choice within 30 feet of it takes Force damage equal to the number rolled; if no other creatures are in range, it takes the damage.


---

### Actions

**Spear.** m,r +4, reach 5 ft. or range 20/60 ft. *Hit:* 6 (1d8 + 2) Piercing damage.


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