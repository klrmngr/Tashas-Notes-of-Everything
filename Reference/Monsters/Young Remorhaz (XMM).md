---
type: pc
race: "Monstrosity"
class:
 - "Young Remorhaz"
subClass:
 - "CR 5"
cover: "Young Remorhaz.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/5
  - source/xmm
---
###### Young Remorhaz
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Young Remorhaz.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 17 | 3 | 10 | 4 |
| **Mod** | +4 | +1 | +3 | -4 | +0 | -3 |

**Speed:** 30 ft., burrow 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., Tremorsense 60 ft., passive Perception 10
**Languages:** —
**Damage Immunities:** cold; fire

---

### Traits

**Heat Aura.** At the end of each of the remorhaz's turns, each creature in a 5-foot Emanation originating from the remorhaz takes 11 (2d10) Fire damage.


---

### Actions

**Bite.** m +7, reach 5 ft. *Hit:* 15 (2d10 + 4) Piercing damage plus 13 (3d8) Fire damage.


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