---
type: pc
race: "Humanoid"
class:
 - "Oracle"
subClass:
 - "CR 4"
cover: "Oracle.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/mot
---
###### Oracle
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Oracle.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 15 (Blessings Of The Gods) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 13 | 16 | 15 |
| **Mod** | +0 | +2 | +1 | +1 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Celestial, Common
**Saving Throws:** Wis +5, Cha +4
**Skills:** Insight +5, Persuasion +4, Religion +5

---

### Traits

**Blessings of the Gods.** While the oracle is wearing no armor and wielding no shield, its AC includes its Wisdom modifier. In addition, a creature that hits the oracle with a melee attack while within 5 feet of it takes 9 (2d8) force damage.


---

### Actions

**Eldritch Touch.** Melee Spell Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) force damage.


---

### Reactions

**Divine Insight (3/Day).** When the oracle or a creature it can see makes an attack roll, a saving throw, or an ability check, the oracle can cause the roll to be made with advantage or disadvantage.


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