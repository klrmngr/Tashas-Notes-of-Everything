---
type: pc
race: "Humanoid (halfling)"
class:
 - "Rilly June"
subClass:
 - "CR 1/2"
cover: "Rilly June.png"
campaign:
locations:
tags:
  - race/halfling
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/1-2
  - source/wtthc
---
###### Rilly June
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Rilly June.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Humanoid (halfling) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 13 (3d6) |
> | :FasUserGroup: Race | Humanoid (halfling) |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 13 | 10 | 13 | 10 |
| **Mod** | +2 | +2 | +1 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common, Halfling
**Saving Throws:** Wis +3
**Skills:** Nature +2, Perception +3, Survival +3

---

### Actions

**Multiattack.** Rilly June makes two Hayfork attacks.

**Hayfork.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Piercing damage.

**G'wan, Git! (1/Day).** wis DC 11, one creature Rilly June can see within 60 feet.  10 (3d6) Psychic damage, and the target has the Frightened condition until the end of its next turn.  Half damage only.


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